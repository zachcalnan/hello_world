# Pandas - dowloand pandas on CMD Prompt: pip install pandas
# pip install jupyterlab
# get data and save it
# input pathway of data into CMD eg: cd C:\Users\ZacharyCalnan\Desktop\Pandas-Demo
# open jupyterlabs by typing in jupyter notebok

# how to display the data frame
import pandas as pd
df = pd.read_csv('Pandas.csv') #turning into a data frame

df.shape # tells us how many rows and columns there are
df.info() #tells us what data tyes there are 

pd.set_option('display.max_rows', 1460) #to display all the rows in the DF
pd.set_option('display.max_columns', 1460) #to display all the columns in the DF
df.head(5) #shows the first 5 rows
df.tail(5) #shows the last 5 rows
