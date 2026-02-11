# EX-NO-6-Pseudo-Random-Number

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
Start the program and import the required libraries.
Seed the random number generator using the current time(i.e) rand(time(0));
Get the number of randon number to generate.
Pass the value for number of iterations and print the numbers.
End the program.

# PROGRAM:
```c
#include <stdio.h>
#include <stdlib.h>
#include <time.h>
int main() {
 srand(time(0));
 int n;
 printf("Enter the number of random numbers to generate: ");
 scanf("%d", &n);
 printf("Generated random numbers:\n");
 for (int i = 0; i < n; i++) {
 int random_number = rand();
 printf("%d\n", random_number);
 }
 return 0;
}

```
# OUTPUT:
<img width="675" height="350" alt="image" src="https://github.com/user-attachments/assets/d1b9749b-e123-4d6c-8a35-740140cdc0d0" />


# RESULT:
Implementation of Pseudorandom Number Generation Using Standard library is successful.
