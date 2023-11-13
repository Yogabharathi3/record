# EX-04-2c
## AIM:
To find the length of the string 'LAPTOP
## ALGORITHM:
1. Set a variable length to 0 (initial length is 0).
2. Set a variable index to 0 (initial index is 0).
3. While the character at index position in the string is not the null character:
    a. Increment the length by 1.
    b. Increment the index by 1.
4. Print or return the length.
## PROGRAM:
```
#include<stdio.h>
#include<string.h>
int main()
{
char a[100];
int i;
scanf("%s",a);
for(i=0;a[i]!='\0';i++);
printf("Length of Str is %d",i);
}
```
## OUTPUT:
![image](https://github.com/Yogabharathi3/record/assets/118899387/c099a5da-49e5-42e9-9d04-f858a9c98fd6)

## RESULT:
Thus the program  has been executed successfully.
