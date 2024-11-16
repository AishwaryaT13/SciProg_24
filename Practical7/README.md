# Practical07

This is the 7th practical of scientific programming where in we perform 2 tasks. In this exercise we find the estimate value of 'e' and the difference between the estimate value of 'e' along with the true value of e.
* As the polynomial order increases the difference gets smaller upto a certain number. The difference kept decreasing till the 12th order, then it grew at the 13th order, then decreased again at the 14th and 15th orders.
* As the order grows, the factorial value climbs exponentially, causing the value of e to become incredibly small. This may not be precisely represented in memory because the computer rounds the number, resulting in tiny mistakes.

## Compile:

## 1. Difference in estimate 'e' value and true value:

```bash
gcc -o facte facte.c -lm

```
# Execute:

```bash
./facte

Please enter the required polynomial order 
1
e is estimated as 2.0000000000, with difference -7.182818e-01

./facte 
Please enter the required polynomial order 
10
e is estimated as 2.7182818011, with difference -2.731266e-08

./facte 
Please enter the required polynomial order 
12
e is estimated as 2.7182818283, with difference -1.728764e-10

./facte 
Please enter the required polynomial order 
13
e is estimated as 2.7182818288, with difference 3.447078e-10

./facte
Please enter the required polynomial order 
14
e is estimated as 2.7182818296, with difference 1.126602e-09

./facte 
Please enter the required polynomial order 
15
e is estimated as 2.7182818301, with difference 1.625527e-09
```

* In exercise 2 we performed dynamic memory allocation with pointers along with array manipulation and pointer handling and freeing the allocated memory. 

* - Fucntion allocateaaray```(**int size**)```was used to take integers as an argument and return pointer to an allocated memory block of that many intergers.
* - Function fillwithones(**int, `*`array**, **int size**) takes a pointer to an array of integers and fills everycell of the array with a one.
* - Function printarray(**int, `*`array**, **int size**) that takes a pointer to an array of integers and prints its elements on screen.
* - Function freepointer(int *array) frees the allocated memory.

## 1. Difference in estimate 'e' value and true value:

```bash
gcc -o point pointer.c -lm

```
# Execute:

```bash
./point

The values in array are:1111111111111111111111111

```
