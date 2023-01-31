# KD-Tree-Nearest-neighbour
The time complexity to find K-nearest neighbourd using brute-force is O(n^3).
Now if we sort the points then complexity can be reduced to O(n^2log(n)).
But by implementing KD Tree the time complexity is drastically reduced to O(klog(n))

To run the program,
'$ gcc main.c file.'
'$ ./a.out'

# Input

The input is in a text format.

1st line : k (how many dimensions)

2nd line : How many data points to be input

3rd line : How many nearest neighbour to find


Then the data points are input line by line

The last line contains the data point for which nearest neighbors are to be found
