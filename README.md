# EX-05-2c
 ## AIM 
To write a C Program to find Sum of Diagonal Elements of a Matrix. 
## ALGORITHM 
1. Start the program. 
2. Read the order of matrix. 
3. Read the matrix elements for the given order. 
4. If row is equal to column, add the matrix value. 
5. Display the final sum. 
6. Stop the program. 
## PROGRAM 
```
#include <stdio.h> 
int main() 
{ 
 int m,n,a[10][10],i,j,sum=0; 
 scanf("%d %d",&m,&n); 
 for(i=1;i<=m;i++) 
 { 
 for(j=1;j<=n;j++) 
 { 
 scanf("%d",&a[i][j]); 
 if(i==j) 
 { 
 printf("%d\n",a[i][j]); 
 sum+=a[i][j]; 
 } 
 } 
 } 
 printf("The Sum of Diagonal Elements of a Matrix = %d",sum); 
 return 0; 
}
```
## OUTPUT
![image](https://github.com/Yogabharathi3/record/assets/118899387/4bd02aa6-4951-4051-87a0-7f4ffb31318e)

## RESULT:
Thus the program  has been executed successfully.
