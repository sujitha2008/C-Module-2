# C-Module-2
# Program 1:
## AIM: 
To write a C program to print numbers from 1 to n(a given number). 
## ALGORITHM: 
```
1) Get a input number n from the user. 
2) using for loop, print the numbers from 1 to n. 
```
## PROGRAM: 
``` 
#include<stdio.h> 
int main() 
{ 
    int num; 
    scanf("%d",&num); 
    for(int i=1;i<=num-1;i++){ 
        printf("%d, ",i); 
    }printf("%d",num); 
    return 0; 
} 
```
## OUTPUT: 
<img width="762" height="105" alt="Screenshot 2025-10-19 213112" 
src="https://github.com/user-attachments/assets/ed4a1fe1-02b0-48d5-8175-c79ec8c9fdda" 
/> 
## RESULT: 
Thus the program to print numbers from 1 to n is executed successfully. 
# Program 2:
## AIM: 
To write a C program to print hollow rectangular pattern. 
## ALGORITHM: 
```
1) Get the inputs row and columns from the user. 
2) using for loop and if else statements, print the hollow rectangle. 
```
## PROGRAM: 
``` 
#include<stdio.h> 
int main() 
{ 
    int row,col; 
    scanf("%d",&row); 
    scanf("%d",&col);  
    for(int i=1;i<=row;i++) 
    { 
        for(int j=1;j<=col;j++) 
        { 
            if(i==1||i==row||j==1||j==col)printf("*"); 
            else printf(" "); 
        }printf("\n"); 
    } 
} 
``` 
## OUTPUT: 
<img width="331" height="192" alt="Screenshot 2025-10-19 222554" 
src="https://github.com/user-attachments/assets/3102b4b7-c50c-4fc0-a3fa-2a178f796d16" 
/> 
## RESULT: 
Thus the C program to print hollow rectangle is executed successfully. 
# Program 3:
## AIM: 
To write a C program to add two numbers using functions . 
## ALGORITHM: 
```
1) Get two numbers as inputs from the user. 
2) Write a function to add those two numbers and call the function using the given numbers 
as arguments.
```
## PROGRAM: 
``` 
#include <stdio.h> 
int nis(int ,int); 
int nis(int n1 ,int n2) 
{ 
printf("The Result of Addition is:%d",n1+n2); 
return 0; 
} 
int main() 
{ 
int num1,num2; 
scanf("%d %d",&num1,&num2); 
nis(num1,num2); 
} 
``` 
## OUTPUT: 
<img width="784" height="107" alt="Screenshot 2025-10-19 223423" 
src="https://github.com/user-attachments/assets/6867b72b-03cf-41c4-88d9-2473a5c7ecd8" 
/> 
## RESULT: 
Thus the C program to add two given numbers using functions is successfully executed. 
# Program 4:
## AIM: 
To write a C program to calculate the sum of digits of a number. 
## ALGORITHM: 
```
1) Get a input number from the user. 
2) separate the digits using modulo operator amd add the digits using loop. 
```
## PROGRAM: 
``` 
#include<stdio.h> 
int main() 
{ 
    int num,sum=0; 
    scanf("%d",&num); 
    do{ 
    sum+=num%10; 
    num=num/10;} 
    while(num>0); 
    printf("%d",sum); 
} 
``` 
## OUTPUT: 
<img width="322" height="145" alt="Screenshot 2025-10-19 224317" 
src="https://github.com/user-attachments/assets/8d49f839-cf5e-4063-bfb6-ef76466c67d5" />  
## RESULT: 
Thus the C program to find the sum of digits of a number is executed successfully. 
# Program 5:
## AIM:
To write a C program to find the factorial of a given number using functions. 
## ALGORITHM: 
```
1) Get a input number from the user. 
2) write a function to find the factorial of a number and call the function using the given 
number as argument. 
```
## PROGRAM: 
``` 
#include<stdio.h> 
void fact(int); 
void fact(int n1) 
{ 
    long long int m=1; 
    for(int i=1;i<=n1;i++) 
    { 
        m*=i; 
    } 
    printf("Factorial value is: %lld",m); 
} 
int main() 
{ 
    int num; 
    scanf("%d",&num); 
    fact(num); 
     
} 
```
## OUTPUT: 
<img width="900" height="96" alt="Screenshot 2025-10-19 225135" 
src="https://github.com/user-attachments/assets/b1014550-5e17-4cf2-b136-14aa98c99d39" 
/>  
## RESULT: 
Thus the C program to find the factorial of a given number using functions is executed 
successfully. 
 
 
 
 
 
 
 
