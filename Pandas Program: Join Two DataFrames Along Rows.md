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

# Create first DataFrame
df1 = pd.DataFrame({
    'Name': ['Alice', 'Bob'],
    'Age': [23, 25]
})

# Create second DataFrame
df2 = pd.DataFrame({
    'Name': ['Charlie', 'David'],
    'Age': [22, 24]
})

# Concatenate DataFrames row-wise
new_df = pd.concat([df1, df2], axis=0)

print("First DataFrame:")
print(df1)

print("\nSecond DataFrame:")
print(df2)

print("\nConcatenated DataFrame:")
print(new_df)
```

## Output
```
First DataFrame:
    Name  Age
0  Alice   23
1    Bob   25

Second DataFrame:
      Name  Age
0  Charlie   22
1    David   24

Concatenated DataFrame:
      Name  Age
0    Alice   23
1      Bob   25
0  Charlie   22
1    David   24
```
## Result
The output has been verified successfully.
