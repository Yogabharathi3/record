# EX-06-2d
## AIM 
Create a structure for student and read the regno,name,no.of.present in the month of jun, july, aug and sep and check the eligibility for writing the examination and display the details using function(use structure variable as global)?
(Total working days=84(no.of.working days jun=21, july=21, aug=21, sep=21) above>=75 percentage eligibility is "yes" otherwise "no". No.of.working days in a monthshould be less than equal to 21).
## ALGORITHM 
1. Include Headers
2. Define Constants 
3. Function Prototype. 
4. Main Function
5. Call the function 
6. Stop the program. 
## PROGRAM 
```
#include<stdio.h>
struct attend
{
int regno;
char name[60];
int jun,july,aug,sept;
}a;
void attendence(struct attend a);
int main(){
scanf("%d %s %d %d %d %d",&a.regno,a.name,&a.jun,&a.july,&a.aug,&a.sept);
attendence(a);
}
void attendence(struct attend a){
float total=(a.jun+a.july+a.aug+a.sept);
if(a.regno<1001) {
float e=(total*100/84);
Name: JAYA BHARATHI | Register212222100013
printf("Reg.no:%d\nName:%s\nTotal.No.of.present
days:%.f\nAttendence:%.2f\n",a.regno,a.name,total,e);
if(e<100 &&
e>50){ printf("eligibility:
yes");
}
else
{
printf("eligibility:no");
}
}
else {
printf("Invalid data:No.of.present days is greater than working day");
}
}
```
## OUTPUT
![image](https://github.com/Yogabharathi3/record/assets/118899387/1a5f4a0c-6796-4822-9d5b-c589492f7f25)

## RESULT:
Thus the program  has been executed successfully.
