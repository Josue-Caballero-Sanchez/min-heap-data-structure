# Min-Heap

This project implements a Min-Heap data structure in C++, supporting operations such as insertion, deletion, decreasing a key, and heap construction from a file. It provides a command-line interface to interact with the heap, allowing users to execute commands to manipulate and display the heap.

### **[Download Project](https://github.com/Josue-Caballero-Sanchez/min-heap-data-structure/archive/refs/heads/master.zip)**

![preview](preview.png)

## Built with

- C++

## How to use the program:

The program takes the following inputs from the keyboard:

S:  
On reading "S" the program stops.

C n:  
on reading "C n" the program creates an empty heap with capacity equal to "n" and waits for the next command.  
-Ex: "C 5" will create an empty heap with a capacity of 5.

R:  
On reading "R" the program reads in the array from the HEAPinput.txt file and creates a heap from the values in HEAPinput.txt by calling the linear time build heap algorithm and waits for the next command.

W:  
on reading "W" the program writes the current heap information to the screen, and waits for the next command.

I f k:  
On reading "I f k" the program inserts an element with key equal to "k" into the current heap. If "f" is set to 2 the program prints out the heap contents before and after the insertion, and if "f" is set to 1 the program does not do any additional printing. The program then waits for the next command.  
-Ex: "I 2 5" will insert an element with key 5 into the heap and print the heap before and after insertion.

D f:  
On reading "D f" the program deletes the element with minimum key from the heap. If "f" is set to 2 the program prints out the heap contents before and after the deletion, and if "f" is set to 1 the program does not do any additional printing. The program then waits for the next command.  
-Ex: "D 1" will delete the element with minimum key and won't print the heap.

K f i v:  
On reading "K f i v" the program decreases the key of element with index "i" to "v". If "f" is set to 2 the program prints out the heap contents before and after the operation, and if "f" is set to 1 the program does not do any additional printing. The program then waits for the next command.  
-Ex: "K 2 3 1" will decrease the key of element 3 to 1.

## HEAPinput.txt file:

The first number in the file will be the arrays size followed by the values in the array.  
**Example HEAPinput.txt file:**  
4  
1  
2  
3  
4

## Running the program:

To run the program first input the "make" command into the terminal. Then input "./run" in the terminal to start the program.
