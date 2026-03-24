# c-module-2b

# EX NO:2-b) Hollow rectangular pattern.

# AIM: 
To write a C program to print hollow rectangular pattern.

# ALGORITHM:
Get the inputs row and columns from the user.
using for loop and if else statements, print the hollow rectangle.

# PROGRAM:
```
#include<stdio.h>
int main()
{
    int row,col;
    scanf("%d",&row);
    scanf("%d",&col); 
    for(int i=1;i<=row;i++)
    {
        for(int j=1;j<=col;j++)
        {
            if(i==1||i==row||j==1||j==col)printf("*");
            else printf(" ");
        }printf("\n");
    }
}
```

# OUTPUT: 
<img width="331" height="192" alt="image" src="https://github.com/user-attachments/assets/dd930ff2-16e0-4635-8d33-f31db785f6d9" />

# RESULT: 
Thus the C program to print hollow rectangle is executed successfully.
