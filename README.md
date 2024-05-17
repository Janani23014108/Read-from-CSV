# Read-from-CSV
## AIM:
To write a python program for reading the csv file content

## ALGORITHM:

### Step 1:
Load the CSV into a DataFrame.

### Step 2:
Print the number of contents to be displayed using df.head().

### Step 3:
The number of rows returned is defined in Pandas option settings.

### Step 4:
Check your system's maximum column with the pd.options.display.max_column statement.

### Step 5:
Increase the maximum number of rows to display the entire DataFrame.


## PROGRAM:
```
#To write a python program for reading content from a CSV file.
#Developed by: J.JANANI
#Register Number: 212223230085

import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:
![329800618-1d338c7d-caac-4d8a-8d34-89de20434b44](https://github.com/Janani23014108/Read-from-CSV/assets/146822085/3ebb50d5-22c1-418b-af56-4031c96b5871)

## RESULT:

Thus the program is written to read the csv file.
