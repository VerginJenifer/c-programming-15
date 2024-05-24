# C program to find the perimeter of the rectangle.
## AIM:
To Write a C program to find the perimeter of the rectangle.
## ALGORITM:
1. Include the standard input-output header file.
2. Define the main function.
3. Declare variables to store the length and width of the rectangle.
4. Prompt the user to enter the length of the rectangle and read the input.
5. Prompt the user to enter the width of the rectangle and read the input.
6. Calculate the perimeter of the rectangle using the formula: perimeter = 2 * (length + width).
7. Print the calculated perimeter.
## PROGRAM:
```
#include <stdio.h>
int main()
{
    float l,b,p;
    scanf("%f%f",&l,&b);
    p=2*(l+b);
    printf("Perimeter of rectangle=%.2f units",p);
    return 0;
}
```
## OUTPUT:
![image](https://github.com/VerginJenifer/c-programming-15/assets/136251012/4bdd02c2-023c-4c43-bcbd-d4c860c384ca)

## RESULT
Thus, a C program to find the perimeter of the rectangle was executed successfully.
