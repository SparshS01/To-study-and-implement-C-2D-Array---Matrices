Sparsh Srivastava

24070123112

EnTC- B1



# Matrix Operations in C++

**Theory:**  
A matrix is a structured arrangement of numbers in rows and columns, forming a rectangular array.  
Matrix operations hold a central place in mathematics, computer science, engineering, and data processing.  
They are applied in solving systems of linear equations, performing transformations in computer graphics, encryption in cryptography, and modeling real-world systems in scientific simulations.  
In programming, matrices are typically represented using 2D arrays, and mastering basic operations like addition, multiplication, transpose, and diagonal sum is essential before progressing to advanced computations such as eigenvalue problems or machine learning algorithms.

This repository contains a variety of C++ programs designed to handle multiple matrix operations, including:

1. **Matrix Addition**  
2. **Row Comparison in a Matrix**  
3. **Sum of Main Diagonal Elements**  
4. **Matrix Multiplication**  
5. **Matrix Input and Display**  
6. **Transpose of a Matrix**  

---

## 1. Matrix Addition

**Description:**  
Adds two matrices together if and only if they have identical dimensions (same number of rows and columns).  
This is one of the most fundamental matrix operations and serves as a starting point for learning more complex tasks.

**Algorithm:**
1. Input `r1`, `c1` for the first matrix and `r2`, `c2` for the second.
2. Check whether `r1 == r2` and `c1 == c2`.
3. If the condition holds:
   - Accept elements for both matrices.
   - Add corresponding elements and store the result in a new matrix.
4. Display the sum matrix.
5. If dimensions do not match, print an error message stating "Not same dimension" and terminate.

---

## 2. Comparing First and Second Rows of a Matrix

**Description:**  
Checks each element of the first row against the corresponding element in the second row to determine if they are the same.  
This method is useful in data verification, duplicate row checking, and simple pattern matching tasks.

**Algorithm:**
1. Input the number of rows `r` and columns `c`.
2. Input the matrix elements row by row.
3. If `r < 2`, display an error message since comparison is not possible.
4. Compare elements of row 0 and row 1 for each column index.
5. Print a message for each column indicating whether the two values match.

---

## 3. Sum of Main Diagonal Elements

**Description:**  
Computes the sum of the elements located on the main diagonal of a square matrix, i.e., positions where row index equals column index.  
This operation is often used in mathematical formulas, trace calculations, and checking properties of special matrices.

**Algorithm:**
1. Input the size `n` for an `n x n` matrix.
2. Input all elements of the matrix.
3. Initialize `sum = 0`.
4. For `i = 0` to `n-1`, add `matrix[i][i]` to `sum`.
5. Display the calculated sum to the user.

---

## 4. Matrix Multiplication

**Description:**  
Multiplies two matrices when the number of columns in the first matrix is equal to the number of rows in the second.  
This operation is widely used in areas such as 3D graphics transformations, neural networks, and linear equation solving.

**Algorithm:**
1. Input `r1`, `c1` for the first matrix and `r2`, `c2` for the second.
2. If `c1 != r2`, display "Matrix multiplication not possible" and stop.
3. If valid:
   - Input both matrices from the user.
   - For each element `(i, j)` in the result matrix:
     - Initialize `result[i][j] = 0`.
     - Add the sum of products `m1[i][k] * m2[k][j]` for `k = 0` to `c1-1`.
4. Display the final product matrix clearly.

---

## 5. Matrix Input and Display (3x3)

**Description:**  
Takes input for a fixed-size `3x3` matrix and displays it in a structured tabular format.  
This is often used for demonstration purposes and small-scale calculations where the size is predefined.

**Algorithm:**
1. Use nested loops over `i` and `j` to read each matrix value.
2. Store the values in a 2D array.
3. Use another nested loop to display the matrix neatly, maintaining row and column alignment.

---

## 6. Transpose of a Matrix

**Description:**  
Creates a new matrix by interchanging the rows and columns of the original matrix.  
This is a basic yet essential operation in many algorithms, including orthogonalization and solving matrix equations.

**Algorithm:**
1. Input the number of rows `r` and columns `c`.
2. Accept elements for the original matrix.
3. Create a new matrix `t` where `t[j][i] = m[i][j]` for all valid `i` and `j`.
4. Display the transposed matrix to the user.

---

## Conclusion

These programs collectively cover the most fundamental matrix operations in C++.  
They illustrate:
- **Addition** for dimensionally compatible matrices.  
- **Row comparison** for detecting similarity.  
- **Diagonal sum** for special element calculations.  
- **Multiplication** for valid matrix dimensions.  
- **Basic input/output** techniques for clear display.  
- **Transpose** for structural transformation of data.  
Mastering these operations lays the groundwork for advanced applications in data science, engineering, and scientific computation.
"""

