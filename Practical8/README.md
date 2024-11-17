# Practical 8

This is the 8th practical of scientific programming, wherethe code executes iterative and recursive version of Euclid's alorithm to calculate teh Greateest Common Divsior(GCD) of two positive integers. In Euclid's algorithm we find gcd by repeatly dividing and taking the remainder.

## Compile:

## 1. GCD with user input:

```bash
gcc -o gcd GCD.c

```
# Execute:

```bash
./gcd

please enter two positive integers:
3
2
Iterative_gcd(3. 2)=1
Recursive_gcd(3. 2)=1
```
## 2. GCD with 2 random integers:

* In this code instead of taking the two positive integer from the user, instead we use 2 random integers.

```bash
gcc -o gcd_rand gcd_Random.c

```
# Execute:

```bash
./gcd_rand

Iterative_gcd(12. 10)=2
Recursive_gcd(12. 10)=2
```