Parallel Quicksort on a hypercube topology: There are different formulations for parallel quicksort on distributed memory machines. One such algorithm for a d-dimensional hypercube is discussed in problem 9.17 of the textbook (page 421). Algorithm 9.9 and Figure 9.21 (pages 422 and 423) in the book further elaborate it. The algorithm is based on recursive halving. In this assignment, you will implement this specific quicksort algorithm on the cluster. For doing so, you will assume a virtual hypercube topology on the cluster nodes.
Compare its performance with the best sequential sorting algorithm (e.g., quicksort) to sort a large input sequence (you can generate the numbers randomly). As in assignment 1, you should plot speed-up versus number of processes graphs for different input data sizes and explain your findings
To compile and run the code:
- STEP 1:```mpicc main.c -o <name of the file>```
- STEP 2:```mpirun <name of the file> input.txt <output file name>```
