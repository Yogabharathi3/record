# EX-05-2a
## AIM 
Write a C Program to print string 'LINUX' using pointer. 
## ALGORITHM 
1. Start the program. 
2. Read a string variable. 
3. Using pointer (*) print the string value. 
4. Stop the program. 
## PROGRAM 
```
#include<stdio.h> 
int main() 
{ 
 char a[30],*p; 
 scanf("%s",a); 
 p=a; 
 printf("The entered string is :: "); 
 while(*p!=0) 
 printf("%c",*p++); 
}
```
## OUTPUT
![image](https://github.com/Yogabharathi3/record/assets/118899387/75347c6e-2cbe-460b-bf27-24869a920c0a)

## RESULT:
Thus the program  has been executed successfully.
