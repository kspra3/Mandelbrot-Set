# FIT3143-Parallel-Computing-Assignment1

1. Compile the mandelbrot.c code and run the program serially for 5 times on a multi-core computer. Use the clock() function in the code to measure the computational time of the program.  
a) You should have 5 sets of measures time results.  
b) From the time results, obtain an average time taken to complete the program
execution.

2. Decide on a parallel partitioning scheme for this program. In your report, with the aid of
diagram/s, describe the partitioning scheme. Justify the selection of the partitioning scheme.

3. Based on your partitioning scheme, modify the code to become a parallel program utilizing
Message Passing Interface (MPI).   
a) Note that all the data needs to be sent back to the master node to be written to the file.  
b) Instead of using the clock() function, use the MPI_Wtime() function to measure the time taken to complete the program execution. The timing code must only be run on the master program. Be sure to place the timing code correctly so that the timings will validly calculate only the computational time and the communication time.  
c) Run the MPI program 5 times on a multi-core computer. Specify the number of logical processes used in the table.  
d) Obtain an average time taken to complete the program execution for part 5(c).

4. Plot your results (serial vs parallel program) on a graph. Evaluate your results for part 5 in your
report to justify the selected partitioning scheme.
