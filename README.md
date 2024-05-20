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

with open("text1.txt", 'r') as fp:
    msg=fp.read()
with open("copy.txt", 'w') as fp1:
    fp1.write(msg)

```
### OUTPUT:
![329847030-c6ce7d10-b50f-444c-9098-dc7567b3a446](https://github.com/shivaa-palaniyappan/Copy-File/assets/146915611/2e113b07-3985-4fa2-a075-c963e25340da)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
