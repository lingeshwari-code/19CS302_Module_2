# EX 10 C program to find the factorial of a given number using a function with arguments and return type.
## DATE:
## AIM:
To write a C program to find the factorial of a given number using a function with arguments and return type.

## Algorithm
1. Start the program.
2. Take input of the number n from the user.
3. Define a function that takes an integer as an argument and returns the factorial of that number.
4. Call the factorial function with n and store the result.
5. Print the factorial and end the program.


## Program:
```
/*
Program to find the factorial of a given number using a function with arguments and return type.
Developed by: Lingeshwari.D
RegisterNumber:  212223060135
*/
#include <stdio.h>

int factorial(int n) {
    int fact = 1, i;
    for(i = 1; i <= n; i++) {
        fact *= i;
    }
    return fact;
}

int main() {
    int n, result;
    scanf("%d", &n);
    result = factorial(n);
    printf("%d\n", result);
    return 0;
}
```

## Output:
![image](https://github.com/user-attachments/assets/1b876ec6-3233-428f-a46d-9573157a340f)

## Result:
Thus the program was executed and the output was verified successfully.
