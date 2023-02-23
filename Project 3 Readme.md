//==============================================================
//CPSC-335-04 (13772) Sorting and Merging Arrays (Project 3)
//Document:       Readme.md (Readme File)
//Due Date:       11/19/2021
//Term:           Fall 2021
//Also Attached:  1) project3.cpp (C++ Code File)
//==============================================================

Project Overview:

This is the Readme file for Project 3 program submission for CPSC 335 Alorithm Engeneering for student Gabriel Cohn-Richer. The project program takes pre-formatted data provided by the instructor, sorts them, and outputs the sorted data in the required format. The program is written in C++ coding language.  It follows the instructions and parametrs given in the instructor-provided document entitled "Project 3 Description.pdf". 


Description:

This program contains the instructor provided sample data files and has the data preloaded into the program.  It is broken into 2 parts, one that contains and processes data for Algorithm 1 (Pattern Sorting), and Algorithm 2 (Merging Sorted Arrays).  Algorithm 1 takes two arrays as input, one containing values to be sorted and the other containing values that may appear in the first array in the order in which the values in the first array should be sorted (all of the values contained in both arrays are treated as strings so they are not restricted to numerical values), performs an in-place sort, and outputs the sorted values from the first array to the console.  Algorithm 2 takes takes an array of four pre-sorted subarrays of integers and merges them into a single array sorted from least to greatest.


Algorithm 1 Example Input:

array 1a = [1, 0, -1, 0, 0, 1, 1, -1, 0, 1]
array 1b = [0, 1, -1]


Algorithm 1 Example Output:

[0, 0, 0, 0, 1, 1, 1, 1, -1, -1]


Algorithm 2 Example Input:

Array_1  =[ [2, 5, 9, 21],
	       [-1, 0, 2],
	       [-10, 81, 121]
	       [4, 6, 12, 20, 150] ]


Algorithm 2 Example Output:

[-10, -1, 0, 2, 2, 4, 5, 6, 9, 12, 20, 21, 81, 121, 150]



User Instructions:

When the program is compiled and launched it will display a menu with 3 options.  Option 1 will display the sample input data for Algorithm 1, process the data, and output the sorted data.  Option 2 will display the sample input data for Algorithm 2, process the data, and output the sorted data.  Option 3 will exit the program.  After data has been output after choosing option 1 or option 2, the user will be taken back to the main menu.  The program will run until the user chooses to exit.
