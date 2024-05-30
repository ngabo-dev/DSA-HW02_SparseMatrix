# Data Structures and Algorithms for Engineers
## Programming Assignment 2: Sparse Matrix

### Project Overview
In this project, I am implementing operations on sparse matrices using any programming language of my choice. The operations include addition, subtraction, and multiplication of sparse matrices.

### Instructions
1. **Download Resources**: 
   Download the code and sample data for this assignment from [this location](insert_link_here).

2. **Organize Files**: 
   Organize the code and the sample input into the following locations:
   - `/dsa/sparse_matrix/code/src/` for code files.
   - `/dsa/sparse_matrix/sample_inputs/` for sample input files.
   Feel free to organize your files as needed.

3. **Implementation**:
    - **Reading Sparse Matrices from File**: 
      Implement code to read a sparse matrix from a file. The format of the file should follow the specified format.
    - **Optimized Data Structure**: 
      My goal is to implement a data structure that optimizes both memory and run time while storing large matrices.
    - **Functions**:
        - `SparseMatrix(char* matrixFilePath)`: Constructor to read and initialize a sparse matrix from a file.
        - `SparseMatrix(int numRows, int numCols)`: Constructor to initialize an empty sparse matrix with given dimensions.
        - `getElement(int currRow, int currCol)`: Get the value at the specified row and column.
        - `setElement(int currRow, int currCol, int value)`: Set the value at the specified row and column.
        - Other functions as needed for matrix operations.
    - **Error Handling**: 
      My code should handle variations in the input file format and raise appropriate errors.

4. **Samples Provided**: 
   A few samples of input files and result files are provided in a zip file.

5. **Grading Method**:
    - Submission points for code that runs and generates output files in the correct format.
    - Points for correctness of the implemented methods.
    - Points for proper use of meaningful internal documentation.

### Note
- Do not use built-in libraries; implement your own custom functions and classes.
- Ensure your code allows the user to select the matrix operation they want to perform and handles input accordingly.
- Remember the mathematical rules for matrix operations and handle exceptions accordingly.
