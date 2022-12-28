# Multithreading-with-Merge-Sort
a C++ Program. Implementation of Multithreading using the concept of Merge Sort Algorithm
# EXPLANATION

# INTRODUCTION:
In this assignment we have used the concept of multithreading with the help of the algorithm of merge sort. 
# MERGE SORT AND MULTIPLE THREADS WHY?
Merge Sort is an algorithm in data structures that works on divide and conquer rule. The reason for using merge sort with multi-threading is because multiple threads are used to performed different task, they are lightweight and is a way to improve parallelism by running the threads simultaneously in different cores of your processor. While merge sort divides an array or list into 2 halves and when it reaches to its depth it starts to merge the array in a sorted way. The time complexity of Merge sort is O(nlogn).
The multiple thread works by sub dividing the program into small chunks of executable threads. Each thread has its programming element that is needed to execute the main program and, each thread is executed one at a time.
# PROGRAM:
In this program we have taken the array from the user and sort it using multithreading with the help of merge sort algorithm. we have taken the core of the CPU (with the help from the Task Manager) as thread or threads (the threads of the CPU are different for every user). we have implemented the code as mentioned above with respect to our threads. for example, the cores of my CPU were 2 so I implemented the code by creating the func () of multithreading which sort the array with the concept of merge sort and join the 2 threads. The code will be implemented according to the use of 2 threads only. Suppose if you have 4 threads then you would use the concept of 4 multiple threads and join them with the help of merge sort to sort the array. 
# Screenshorts
# Cores and Logical Processor

# MAC Adress
