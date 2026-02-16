# 113-data-handling-
pip install pandas
import pandas as pd
df = pd.DataFrames
'Name': TAlice', 'Bob', 'David].
'Age': [25, 32, 471
'City': 'NY', 'LA', 'NY7
'Salary':[70000, 90000, 120000]
1)
print(df)
print(df.head), df.shape)print(df.sort values('Age))print(dffdfIAge1>301)dept = pd.DataFrame(
'Name': I'Alice', 'Bob', 'David'l.
'Dept: THR', 'Eng, 'Eng
)
merged = pd.merge(df, dept, on=/Name')
print(merged)
print(df.groupby('City)TSalaryl.mean())Output:
Name Age City Salary
0 Alice 25 NY 70000
Bob 32 LA 90000
2 David 47 NY 120000
Name Age City Salary
0 Alice 25 NY 70000
Bob 32LA 90000
2 David 47 NY 120000(3, 4)
Name Age City Salary
0 Alice 25 NY 70000
1 Bob 32 LA 90000
2 David 47 NY 120000
Name Age City Salary
Bob 32 LA 90000
2 David 47NY 120000
Name Age City Salary Dept
0 Alice 25 NY 70000 HR
1 Bob 32 LA 90000 Eng
2 David 47 NY 120000 Eng
City
LA 90000.0
NY 95000.0
Name: Salarv. dtype: float64
