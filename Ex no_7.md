# EX 7 C Program to Print a right triangle star Pattern
## DATE:
## AIM:
To write a C Program to Print a right triangle star Pattern

## Algorithm
1.Start the program.
2.Declare an integer variable n for the number of rows. 
3.Take input from the user for the value of n. 
4.Use a nested loop: Outer loop runs from 1 to n (for each row). Inner loop runs from 1 to the current row number and prints stars (*).
5.End the program.


## Program:
```
/*
Program to Print a right triangle star Pattern
Developed by: Lingeshwari.D
RegisterNumber:  212223060135
*/
#include <stdio.h>

int main() {
    int n, i, j;
    scanf("%d", &n);
    for(i = 1; i <= n; i++) {
        for(j = 1; j <= i; j++) {
            printf("*");
        }
        printf("\n");
    }
    return 0;
}
```

## Output:
![image](https://github.com/user-attachments/assets/b9fea126-dcef-445e-a163-56920219cf11)
## Result:
Thus the program was executed and the output was verified successfully.
