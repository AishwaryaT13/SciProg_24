## PRACTICAL NUMBER 3

This is the 3rd practical of Scientific programming. In this practical, the program calculates the approximate area under the curve of the tangent function between 0° and 60° using the trapezoidal rule.

## Compile:

* gcc -o trap2 trap2.c -lm


## Execute:

* ./trap2

# output:

TanArr[0] = 0.000000<br>
TanArr[1] = 0.087489<br>
TanArr[2] = 0.176327<br>
TanArr[3] = 0.267949<br>
TanArr[4] = 0.363970<br>
TanArr[5] = 0.466308<br>
TanArr[6] = 0.577350<br>
TanArr[7] = 0.700208<br>
TanArr[8] = 0.839100<br>
TanArr[9] = 1.000000<br>
TanArr[10] = 1.191754<br>
TanArr[11] = 1.428148<br>

Initial area (sum at x(0) and x(12)) = 0.000000<br>
The value of the sum after the loop is: 14.197204<br>
 
 Trapezoidal result is: 0.619470<br>
Real result is:0.693147<br>


The program calculates and prints the tangent values for each interval, followed by the intermediate area computed using the trapezoidal rule. It then displays the final trapezoidal result and compares it with the actual value of log(2).
