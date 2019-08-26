
 
 What is CSV file?. 
 
CSV stands for "comma-separated values”.  In CSV file each value is separated by comma. Here we have following assumption about data in CSV file .  In first row we have columns name that are separated by comma .  From second row on-ward we contain data corresponding each columns name for Example: 

Text:
name,roll <br>
a,14 <br>
f,78 <br>

Save it as example.csv 
 
Here we call first line as Header . 
 
If you open it in spreadsheet program like Excel . it will look like as follow : 

| name | roll |
|------|------|
| a    | 14   |
| f    | 78   |

Write implementation of following operation in Either C++ or  C . 
 
 
1. Create: this function accepts column name as input argument and creates csv file  .     Input : Name , roll_no  Output: create a csv file with Header Name and Roll_no 
 
2. IsSameStucture: Compare two CSV files whether they are same structure or not.       by same structure we mean that number column in both file is same and there is one to one mapping of column name.  

 
3. IsDuplicate: Check if Duplicate row data entries exist in CSV file. 
 
4.  RemoveDuplicate: Remove Duplicate row entry in CSV file.  
 


 
 
