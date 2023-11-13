# EX-04-2d
## AIM:
Write a C program to accept a line from user and count number of white or blank spaces from the line using function.
## ALGORITHM:
1. Start the program. 
2. Read a string variable. 
3. Using for loop, inspect the string character by character. 
4. Whenever a space is encountered increment count by 1. 
5. Display the result. 
6. Stop the program.
## PROGRAM:
```
#include<stdio.h>
int main()
{
  char a[500];
  scanf("%[^\n]",a);
  int i,c=0;
  for(i=0;a[i]!='\0';i++)
  {
      if(a[i]==' ')
      {
          c=c+1;
      }
  }
  printf("White spaces: %d",c);
  return 0;
}
```
## OUTPUT:
![image](https://github.com/Yogabharathi3/record/assets/118899387/002349d3-7229-46d8-b06a-31ae32000bfb)
## RESULT:
Thus the program  has been executed successfully.
