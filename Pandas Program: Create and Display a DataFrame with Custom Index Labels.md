# Pandas Program: Create and Display a DataFrame with Custom Index Labels

## 🎯 Aim

To create and display a **DataFrame** using the **Pandas** library in Python from a given dictionary, and apply specific index labels to the rows.

---

## 🧠 Algorithm

1. **Import Libraries**: Import the required libraries – `pandas` and `numpy`.
2. **Create Dictionary**: Define a dictionary `exam_data` with keys: `'name'`, `'score'`, `'attempts'`, and `'qualify'`.
3. **Index Labels**: Create a list of custom index labels called `labels`.
4. **Create DataFrame**: Use `pd.DataFrame()` to create the DataFrame by passing the dictionary and index labels.
5. **Display Output**: Display the DataFrame using `print()` or by simply calling the DataFrame variable.

---

## 💻 Program
```
import pandas as pd

# Dictionary containing data
data = {
    'Name': ['Alice', 'Bob', 'Charlie'],
    'Age': [23, 25, 22],
    'City': ['New York', 'London', 'Paris']
}

# Create DataFrame with custom index labels
df = pd.DataFrame(data, index=['A', 'B', 'C'])

# Display the DataFrame
print(df)
```

## Output
```
      Name  Age      City
A    Alice   23  New York
B      Bob   25    London
C  Charlie   22     Paris
```
## Result
The output has been verified successfully.
