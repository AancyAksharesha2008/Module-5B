# NumPy Program: Column-wise Sorting of a 2D Array

## 🎯 Aim
To write a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

## 🧠 Algorithm

1. **Import NumPy**: Start by importing the NumPy library.
2. **Get Input**: Accept a 2D NumPy array from the user.
3. **Sort Column-wise**: Use the `np.sort()` function with `axis=0` to sort each column in ascending order.
4. **Store Result**: Store the sorted result in a new array.
5. **Display Output**: Print the original array and the column-wise sorted array.

## 🧾 Program
```
import numpy as np

# Create a 2D array
arr = np.array([[9, 4, 7],
                [2, 8, 1],
                [5, 3, 6]])

print("Original Array:")
print(arr)

# Sort each column in ascending order
sorted_arr = np.sort(arr, axis=0)

print("\nArray after sorting each column:")
print(sorted_arr)
```

## 
```
Original Array:
[[9 4 7]
 [2 8 1]
 [5 3 6]]

Array after sorting each column:
[[2 3 1]
 [5 4 6]
 [9 8 7]]
```

## Result
The output has been verified successfully.
