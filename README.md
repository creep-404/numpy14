# NumPy

This repository contains solutions to NumPy programming exercises covering array properties, statistical methods, indexing, reshaping, and arithmetic operations.

## Questions Covered

### 1. Array Properties
- Create a 2D array of shape (5, 6) with random integers between 10 and 100
- Print shape, size, and dtype

### 2. Statistical Methods - Basic
- Generate a 1D array of 20 random numbers between 1 and 50
- Find minimum value and its index (argmin)
- Find maximum value and its index (argmax)
- Calculate sum, mean, and standard deviation

### 3. Statistical Methods on 2D Array
- Create a 4×5 matrix of random integers between 20 and 80
- Find minimum, maximum, sum, mean, and standard deviation
- Calculate sum of each row and each column

### 4. Reshape
- Create a 1D array from 1 to 24 using `np.arange()`
- Reshape into (4, 6)
- Reshape into (3, 8)
- Reshape into (2, 3, 4) (3D array)
- Print all reshaped arrays with their shapes

### 5. NumPy Indexing - 1D & 2D
- Extract first row
- Extract last column
- Extract center 2×2 submatrix
- Extract all even numbers using boolean indexing

### 6. Advanced Indexing
- Create a 5×5 matrix of random integers between 1 and 100
- Print diagonal elements
- Print elements greater than 50
- Replace all elements less than 30 with 0
- Print the modified array

### 7. Arithmetic Operations
- Addition, subtraction, multiplication, division of two arrays
- Element-wise power (`**`)
- Modulo operation (`%`)

### 8. Matrix Multiplication
- Element-wise multiplication (`*`)
- Matrix multiplication (`@` or `np.dot()`)
- Compare and explain the difference between the two

### 9. Combined - Properties + Operations + Indexing
- Generate a 6×6 matrix using `np.random.randn()`
- Print shape, size, and dtype
- Find index of maximum and minimum value
- Extract top-left 3×3 submatrix
- Replace negative numbers with their absolute value
- Print mean of the modified matrix

### 10. Mini Project - Student Performance Analysis
- Generate a 2D array of shape (10 students × 5 subjects) with random marks between 30 and 100
- Calculate total marks and average for each student
- Find student with highest and lowest total marks (argmax/argmin)
- Calculate overall class mean and standard deviation
- Reshape array and extract marks of top 3 students

## NumPy Functions Used

- `np.array()`
- `np.arange()`
- `np.random.randint()`
- `np.random.randn()`
- `reshape()`
- `argmin()`
- `argmax()`
- `sum()`
- `mean()`
- `std()`
- `min()`
- `max()`
- `diag()`
- `np.dot()` / `@`
- `np.abs()`
- `shape`
- `size`
- `dtype`