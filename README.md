# covid_19-dataset
A dataset related to covid-19 pandemic.

I have taken a small dataset of Covid-19 for our better understanding purpose.

The data used here is till 29 April 2020.

I analyzed this data using the Pandas DataFrame.



The commands that I used in this project :

* import pandas as pd -- To import Pandas library
* pd.read_csv - To import the CSV file in Jupyter notebook
* df.count() - It counts the no. of non-null values of each column.
* df.isnull().sum() - It detects the missing values from the dataframe.
* import seaborn as sns - To import the Seaborn library.
* import matplotlib.pyplot as plt - To import the Matplotlib library.
* sns.heatmap(df.isnull()) - It will show the all columns & missing values in them in heat map form.
* plt.show() - To show the plot.
* df.groupby(‘Col_name’) - To form groups of all unique values of the column.
* df.sort_values(by= ['Col_name'] ) - Sort the entire dataframe by the values of the given column.     
* df[df.Col_1 = = ‘Element1’] - Filtering – We are accessing all records with Element1 only of Col_1.


