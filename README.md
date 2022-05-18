# Doubly Linked List in C

Write an ANSI-C program to implement a full-fledged doubly linked list data structure. In a doubly linked list, each node has two
pointers, one point to the next node in the chain and one points to the node preceding it. The first node’s pointer to previous node is NULL

# Implementation

Opens a data file data.txt using FILE IO in C. The file contains lines of integers, each line contains exactly two integers. (Stream and FILE IO is a topic that is usually in the syllabus but is skipped this semester.)

• Reads the data file line by line, and store the two integers in each line into a structure of type twoInts. The structures are maintained by arr, which is an array of pointers to struct twoInts. The structure twoInts contains two integer data members.

• the structure pointed by the pointer in arr[i] gets the two values for its data members from the two integers in the i’th line of the file. For example, the structure pointed in arr[0] gets the two values for its members from the two integers in the first line of the file, arr[1] gets the two values for its members from the two integers in the second line, and so on.
