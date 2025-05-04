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

arr = np.array([[12, 5, 7],
                [1, 9, 3],
                [8, 6, 4]])

sorted_arr = np.sort(arr, axis=0)

print("Original Array:\n", arr)
print("Column-wise Sorted Array:\n", sorted_arr)
```

## Output
```
Original Array:
 [[12  5  7]
 [ 1  9  3]
 [ 8  6  4]]
Column-wise Sorted Array:
 [[ 1  5  3]
 [ 8  6  4]
 [12  9  7]]
```

## Result
Thus, we have written  a **NumPy** program that sorts the elements in each column of a given 2D array in ascending order.

