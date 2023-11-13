# EX-05-2d
## AIM 
To write a C Program to find a substring within a string and if found to display its 
starting position. 
## ALGORITHM 
1. Start the program. 
2. Read two string variables. 
3. Using for loops check whether the second string is present in first string. 
4. If found then display its position. 
5. Stop the program. 
## PROGRAM 
```
#include <stdio.h> 
int main() 
{ 
 char str1[80], str2[80]; 
 int l, i, j; 
 scanf("%s",str1); 
 scanf("%s",str2); 
 for (l = 0; str2[l] != '\0'; l++); 
 for (i = 0, j = 0; str1[i] != '\0' && str2[j] != '\0'; i++) 
 { 
 if (str1[i] == str2[j]) 
 { 
 j++; 
 } 
 else 
 { 
 j = 0; 
 } 
 } 
 if (j == l) 
 printf("Substring found at position %d", i - j + 17); 
 else 
 printf("Substring not found"); 
 return 0; 
}
```
## OUTPUT
![image](https://github.com/Yogabharathi3/record/assets/118899387/7f57109f-7a63-4450-8fd3-e54703dd4a8b)

## RESULT:
Thus the program  has been executed successfully.
