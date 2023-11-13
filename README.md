# EX-06-2b
## AIM 
Write a C program to count total number of odd elements in the following
array 33,55,302,231,250 using malloc()
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
#include<stdlib.h>
int main()
{
int i,odd=0,
*ptr;
ptr=(int*)malloc(5*sizeof(int));
ptr[0]=33;
ptr[1]=55;
ptr[2]=302;
ptr[3]=231;
ptr[4]=250;
for(i=0; i<5; i++)
{
if(ptr[i]%2!= 0)
{
odd++;
}
}
printf("Total odd elements:%d"
, odd);
return 0;
}
```
## OUTPUT
![image](https://github.com/Yogabharathi3/record/assets/118899387/e9f19fd4-522c-49ac-af5c-d8aa8bab4e8a)


## RESULT:
Thus the program  has been executed successfully.
