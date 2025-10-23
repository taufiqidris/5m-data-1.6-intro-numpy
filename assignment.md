# Assignment

## Brief

Write the Python codes for the following questions.

## Instructions

Paste the answer as Python in the answer code section below each question.

### Question 1

Given the following numpy array:

```python
arr = np.array([1, 2, 3, 4, 5])
```

Write a Python code to multiply each element in the array by 2.

Answer:

```python
arr = np.array([1, 2, 3, 4, 5])
multiply_by_2 = arr * 2
print(multiply_by_2)
```

### Question 2

Given the following 2D numpy array:

```python
arr = np.array([[1, 2, 3], [4, 5, 6], [7, 8, 9]])
```

Write a Python code to select the second row of the array.

Answer:

```python
arr = np.array([[1, 2, 3], [4, 5, 6], [7, 8, 9]])
select_second_row = arr[1]
print(select_second_row)
```

### Question 3

Create a 2D numpy array of shape (5, 5) filled with the number 1.

Answer:

```python
arr_num1 = np.ones((5,5))
print(arr_num1)
```

### Question 4

Given the following 2D numpy array:

```python
arr = np.array([[1, 2, 3], [4, 5, 6], [7, 8, 9]])
```

Write a Python code to calculate the sum of all the elements in each row.

Answer:

```python
arr = np.array([[1, 2, 3], [4, 5, 6], [7, 8, 9]])
sum_each_row = np.sum(arr, axis = 1) # axis = 1 to sum across each row
print(sum_each_row)
```

### Question 5

Given the following 2D numpy array:

```python
arr = np.array([[1, 2, 3], [4, 5, 6], [7, 8, 9]])
```

Write a Python code to calculate the average of all the elements.

Answer:

```python
arr = np.array([[1, 2, 3], [4, 5, 6], [7, 8, 9]])
average = np.mean(arr)
print(average)
```

## Submission

- Submit the URL of the GitHub Repository that contains your work to NTU black board.
- Should you reference the work of your classmate(s) or online resources, give them credit by adding either the name of your classmate or URL.
