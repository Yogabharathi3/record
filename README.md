# EX-05-2b
## AIM 
Write a C Program to swap the values m = 20, n=45 using function pointers. 
## ALGORITHM 
1. Start the program. 
2. Read two numbers. 
3. Pass the address of the two numbers to the function. 
4. Swap the two numbers. 
5. Display the result. 
6. Stop the program. 
## PROGRAM 
```
#include <stdio.h> 
void swap(int *, int *); 
int main() 
{ 
 int a=20,b=45; 
 printf("m is %d, n is %d\n",a,b); 
 swap(&a,&b); 
 printf("m is %d, n is %d",a,b); 
} 
void swap (int *a, int *b) 
{ 
 *a=*a+*b; 
 *b=*a-*b; 
 *a=*a-*b; 
}
```
## OUTPUT
![image](https://github.com/Yogabharathi3/record/assets/118899387/f5dfbf30-0839-4fc5-ab4f-930403c1febc)
## RESULT:
Thus the program  has been executed successfully.
