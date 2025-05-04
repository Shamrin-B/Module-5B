# 🧪 Pandas Program: Join Two DataFrames Along Rows

## 🎯 AIM

To write a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame.

---

## 🧠 ALGORITHM

1. **Import Libraries**: Import the `pandas` library.
2. **Create First DataFrame**: Use a dictionary to create `student_data1`.
3. **Create Second DataFrame**: Use another dictionary to create `student_data2`.
4. **Concatenate DataFrames**: Use `pd.concat()` with `axis=0` to concatenate both DataFrames row-wise.
5. **Display Result**: Print the new combined DataFrame.

---

## 💻 Program
```
import pandas as pd

student_data1 = {
    'name': ['John', 'Anna', 'Peter'],
    'age': [23, 24, 21],
    'score': [88, 92, 85]
}

student_data2 = {
    'name': ['Lucy', 'Tom', 'Emma'],
    'age': [22, 25, 20],
    'score': [91, 78, 89]
}

df1 = pd.DataFrame(student_data1)
df2 = pd.DataFrame(student_data2)

result_df = pd.concat([df1, df2], axis=0, ignore_index=True)

print(result_df)
```

## Output
```
    name  age  score
0   John   23     88
1   Anna   24     92
2  Peter   21     85
3   Lucy   22     91
4    Tom   25     78
5   Emma   20     89
```
## Result
Thus, we have written a Python program using Pandas to **join two DataFrames along rows** (row-wise concatenation) and assign all data to a new DataFrame.

