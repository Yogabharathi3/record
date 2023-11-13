# EX-06-2c
## AIM 
Create a C Program to store the student information and display it using structure
struct student
{ char
name[50];int
roll;
float marks;
};
## ALGORITHM 
1. Include Headers
2. Define Constants 
3. Function Prototype. 
4. Main Function
5. Call the function 
6. Stop the program. 
## PROGRAM 
```

#include <stdio.h>
struct student {
char name[50];
int roll;
float marks;
} s;
int main()
{
scanf("%s %d %f"
,s.name,&s.roll,&s.marks);
printf("Displaying Information:\n");
printf("Name: ");
printf("%s\n"
, s.name);
printf("Roll number: %d\n"
,
s.roll);printf("Marks: %.1f\n"
,
s.marks);
return 0;
}
```
## OUTPUT
![image](https://github.com/Yogabharathi3/record/assets/118899387/bce51327-ed80-4c54-b790-8885f26d81dc)
## RESULT:
Thus the program  has been executed successfully.
