# Read-from-CSV

## AIM:
To read from nba.csv file and the print the result.
## ALGORITHM:
### Step 1:
Read the CSV file using read_csv method.
### Step 2:
Use head and tail method to get the required contents from the file.
### Step 3:
Use len() method to get the number of rows and columns.
### Step 4:
Print the output.
## PROGRAM:
```
'''
Developed by:Pradeep raj.
Register Number:212222240073
'''
import pandas as p
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:
![image](https://github.com/Pradeeppachiyappan/Read-from-CSV/assets/118707347/809c836b-6c3e-4c82-905c-8855e30ba021)

## RESULT:
Thus,the experiment was executed successfully.
