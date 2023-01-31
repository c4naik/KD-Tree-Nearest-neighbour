# KD-Tree-Nearest-neighbour
The time complexity to find K-nearest neighbourd using brute-force is O(n^3).
Now if we sort the points then complexity can be reduced to O(n^2log(n)).
But by implementing KD Tree the time complexity is drastically reduced to O(klog(n))


![Screen-Shot-2014-07-18-at-12 00 36-pm(1)](https://user-images.githubusercontent.com/102814951/215682772-fca42650-0521-46d1-869f-987aebad0cb9.png)

To run the program,

>$ cc dsa2_kdtree.c -o kdtree

>$ ./kdtree

# Input

The input is in a text format.

1st line : k (how many dimensions)

2nd line : How many data points to be input

3rd line : How many nearest neighbour to find

Then the data points are input line by line

The last line contains the data point for which nearest neighbors are to be found
