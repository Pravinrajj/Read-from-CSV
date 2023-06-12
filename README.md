# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file
## ALGORITHM:
### Step 1:
Import pandas as pd.
### Step 2:
Read the CSV file using read_csv method.
### Step 3:
Use head and tail method to get the required contents from the file.
### Step 4:
Use len() method to get the number of rows and columns.
### Step 5: 
Print the output.

## PROGRAM:
```
import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:
![Screenshot (125)](https://github.com/Pravinrajj/Read-from-CSV/assets/117917674/f2551254-f3ac-42a5-a6a5-a9c7f3fb3291)

## RESULT:
Thus a python program is written to read the contents of a CSV file
