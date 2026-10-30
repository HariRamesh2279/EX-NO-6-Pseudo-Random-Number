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
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main() {
    int n, i;

    srand(time(0));

    printf("Enter the number of random numbers: ");
    scanf("%d", &n);

    printf("Random numbers are:\n");

    for (i = 0; i < n; i++) {
        printf("%d\n", rand());
    }

    return 0;
}
# OUTPUT:
<img width="1917" height="1038" alt="Screenshot 2026-10-30 134631" src="https://github.com/user-attachments/assets/177053e2-6eb4-41c4-8e8d-dfd8bb9b8ea9" />

