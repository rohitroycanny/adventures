```python
""""import csv
file = open('Salary_Data.csv')
    type(file)
    
 csvreader = csv.reader(file)


header = []
header = next(csvreader)
header

rows = []
for row in csvreader:
        rows.append(row)
rows
""""
```


```python
""""import csv
file = open("Salary_Data.csv")
csvreader = csv.reader(file)
header = next(csvreader)
print(header)
rows = []
for row in csvreader:
    rows.append(row)
print(rows)
file.close()""""
```


```python
# .readlines()
"""""with open('Salary_Data.csv') as file:
    content = file.readlines()
header = content[:1]
rows = content[1:]
print(header)
print(rows)""""
```

```python
""""import pandas as pd
data= pd.read_csv("Salary_Data.csv")
data
data.columns
data.Salary
""""
```
