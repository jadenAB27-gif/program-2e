# program-2-e-
C module 2
EX NO:2-e) Factorial of a given number using funcions. 

Date: 26/03/26
Name: JADEN SAMUEL ABRAHAM
Ref no: 25003451

AIM: To write a C program to find the factorial of a given number using functions.

ALGORITHM:

1) Get a input number from the user.
2) write a function to find the factorial of a number and call the function using the given number as argument.

PROGRAM:
```
#include<stdio.h>
void fact(int);
void fact(int n1)
{
    long long int m=1;
    for(int i=1;i<=n1;i++)
    {
        m*=i;
    }
    printf("Factorial value is: %lld",m);
}
int main()
{
    int num;
    scanf("%d",&num);
    fact(num);
    
}
```

OUTPUT:
<img width="900" height="96" alt="Screenshot 2025-10-19 225135" src="https://github.com/user-attachments/assets/b1014550-5e17-4cf2-b136-14aa98c99d39" />

RESULT:
Thus the C program to find the factorial of a given number using functions is executed successfully.






