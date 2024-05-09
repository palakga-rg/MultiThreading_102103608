# Multi-Threading-102103608

The "Matrix Multiplication Performance Benchmark" project evaluates the impact of multi-threading on matrix multiplication tasks. Using Python libraries like NumPy, threading, and Pandas, the project generates random matrices and measures the execution time of matrix multiplication with varying numbers of threads (1 to 8). The results are analyzed and visualized to understand how concurrency affects performance. This project offers insights into optimizing computational tasks involving matrix operations.

Function explanation:
1. **generate_random_matrices(n, size)**:
   - Generates `n` random matrices of size `size x size`.

2. **multiply_matrices(matrices)**:
   - Multiplies a list of matrices together, starting with a constant matrix.

3. **perform_multiplication_with_threads(num_threads)**:
   - Performs matrix multiplication using multiple threads, dividing the task among them for parallel computation.

The table corresponding to the time taken with respect to number of threads is as follows:
![image](https://github.com/Kushagrekaushik/MultiThreading_102103608/assets/100528019/6a1506ff-ef2f-4796-8146-80a23ff26dba)



Graph:
![image](https://github.com/Kushagrekaushik/MultiThreading_102103608/assets/100528019/8549884d-df3c-46d0-85cf-50919792d0bd)


![download]: https://github.com/Kushagrekaushik/MultiThreading_102103608.git)
