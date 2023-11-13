# EX-04-2a
## AIM:
Write a Program to check whether a given Value=Y is upper case, lower case, number or special character using conditional operator?
## ALGORITHM:
1. Get Input
2. Check for Uppercase
3. Check for lowercase
4. Check for Number
5. Check for Special Character
6. End the program
## PROGRAM:
```
#include <stdio.h>
int main()
{
char a='A';
((a>='a')&&(a<'z'))?printf("Lower"):((a>='A')&&(a<'Z'))?printf("Upper"):((a>1)&&(a<=40))
?printf("Symbol"):printf("Number");
}
```
## OUTPUT:
![image](https://github.com/Yogabharathi3/record/assets/118899387/165c0661-0427-4cfe-9bd0-33618cf278a4)

## RESULT:
Thus the program  has been executed successfully.
