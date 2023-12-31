# Read-from-CSV

## AIM:
 TO Read csv file
 
## ALGORITHM:
## Step 1:
Import the pandas library as "pd".

## Step 2:
Read the CSV file "nba.csv" using read_csv() method and assign it to the variable "df".

## Step 3:
Use head and tail method to get the required contents from the file.

## Step 4:
Use len() method to get the number of rows and columns and 'shape' attribute to find the dimensions of the dataframe.

## Step 5:
Print the output and end the program.

## PROGRAM:
```python

#Program to for getting the word count from a text.
#Developed by:PRAVIN KUMAR A
#Register Number:212223230155
import pandas as pd
df=pd.read_csv('/Users/pravi/Downloads/nba.csv')
print(df.head(10))
print(df.tail(5))
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
print(df.shape)
```
## OUTPUT:

![6](https://github.com/RAVENPRAVIN/Read-from-CSV/assets/146820534/7f6e368c-8adf-468d-9cee-f470dbe3398e)

## RESULT:
Thus a python program is written to read the contents of a CSV file.
