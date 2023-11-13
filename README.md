# EX-06-2a
## AIM 
Write a C program to find area of a circle & perimeter of a circle for the radius 35 using
pointer
## ALGORITHM 
1. Include Headers
2. Define Constants 
3. Function Prototype. 
4. Main Function
5. Call the function 
6. Stop the program. 
## PROGRAM 
```
# include <stdio.h>
int main()
{
float r,*a=&r;
scanf("%f",&r);
float area = (3.14*(*a)*(*a));
float peri = (2*3.14*(*a));
printf("Area of Circle = %.2f\n",area);
printf("Perimeter of Circle = %.2f",peri);
}
```
## OUTPUT
![image](https://github.com/Yogabharathi3/record/assets/118899387/79749e92-975b-4f31-9d5b-10038f834c79)

## RESULT:
Thus the program  has been executed successfully.
