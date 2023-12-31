# Read-from-CSV

## AIM:
To read content from a CSV file using pandas.
## ALGORITHM:
### Step 1:
Library Import:

Import the Pandas library using import pandas as pd.
### Step 2:
Read CSV File:

Use the pd.read_csv() function to read a CSV file located at a specified path into a Pandas DataFrame (df).
### Step 3:
Print First 10 Rows:

Print a message indicating the display of the first 10 rows. Print the first 10 rows of the DataFrame using df.head(10).
### Step 4:
Print Last 5 Rows:

Print a message indicating the display of the last 5 rows. Print the last 5 rows of the DataFrame using df.tail().
### Step 5:
Print Number of Columns and Rows:

Print a message indicating the display of the number of columns. Print the number of columns in the DataFrame using len(df.axes[0]). Print a message indicating the display of the number of rows. Print the number of rows in the DataFrame using len(df.axes[1]).
### Step 6:
End of Program:

The provided code represents the conclusion of the program execution. The code represents the end of the program, and the execution flow stops here.
## PROGRAM:
```
# Program to read content from a CSV file using pandas.
# Developed By : K Kesava sai
# Register Number : 212223230105
import pandas as pd

df = pd.read_csv(r"C:\Users\admin\Downloads\cars (1) (1).csv")

print("First 10 Rows:")
print(df.head(10))

print("\nLast 5 Rows:")
print(df.tail())

print("\nNumber of Columns:", len(df.axes[0]))
print("Number of Rows:", len(df.axes[1]))

```
## OUTPUT:
![image](https://github.com/Kesavasai20/Read-from-CSV/assets/138849303/4e77982b-4083-4f1a-b805-5bec9bffa3d1)

## RESULT:
Successfully executed the program to read the content from a csv using pandas.
