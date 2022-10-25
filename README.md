# hw-9

#### Instructions
Answer the hw in files called q1.c, q2.c, etc
Submit compile-able code
You may work in pairs, but both partners must have commits in the repo.

#### Questions
1. Write a function that determines the maximum and minimum values from a one-dimensional array. Assume that the corresponding function prototype statement is

   <code>void ranges(int x[], int npts, int *max_ptr, int *min_ptr)</code>

   where ```npts``` contain the number of values in array ```x```, and ```max_ptr``` and ```min_ptr``` are pointers to the variables in which to store the maximum and minimum values in the array.

   Have a main that first accept the number of points followed by an array of integers (max 10). Your main should also print out the max and min values of the array after calling the ranges function.

2. (K&R Exercise 5-13) Write the program <code>tail</code>, which prints the last ```n``` lines of its input. By default, ```n``` is 10, let us say, but it can be changed by an optional argument, so that

    <code>tail -n</code>

    prints the last ```n``` lines. The program should behave rationally no matter how unreasonable the input or the value of n. Write the program so it makes the best use of available storage; lines should be stored as in the sorting program of Seciton 5.6, not in a two-dimensional array of fixed size.

3. Using the point struct that we used in class, write a program that will compute 11 points of a quadratic curve in the form of ```ax^2+bx+c``` from -5 to 5. Prompt the user to input values for a, b, and c. Store these points in a struct array and print the points.

    Have the main accept ```a```, ```b```, and ```c``` (which are whole numbers to make things easier) using argc and argv.
    
4. Find an interesting statistic and create a structure in C storing those statistics. Write 2 functions that does interesting analystics for those statistics. Be sure to print out these analytics.

    For example, the top 25 snow storms in NYC can be stored in a structure containing the month, day, year and the number of inches it snowed. Two functions could be to find the average of the top snow storms and to sort the snowstorms starting with the most recent.

    Note: You may hard code these statistics in a global or in your main.

    Bonus (+5 points): Find an actual data file that you ingest with your program using functions like fopen from chapter7.


#### Grading
Output - 50% Code Quality - 50%
