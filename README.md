# EXP-11 Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Load the CSV into a DataFrame.
### Step 2: 
 Print the number of contents to be displayed using df.head()
### Step 3: 
The number of rows returned is defined in Pandas option settings
### Step 4:  
Check your system's maximum column with the pd.options.display.max_column statement.
### Step 5: 
Increase the maximum number of rows to display the entire DataFrame
### Step 6: 
End the program.
## PROGRAM:
```
#To write a python program for reading content from a CSV file.
#Developed by: SHIVAA PALANIYAPPAN V
#Register Number: 212223110050

import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))

```
### OUTPUT:
![329831705-6b92d7bc-4917-445d-815a-9296bdd18ab1](https://github.com/shivaa-palaniyappan/Copy-File/assets/146915611/4e75e82c-0038-4512-a641-d7def490a242)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
