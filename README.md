# EX-3-A-FUNCTIONS
## AIM :
write a program to prepare EMI calculation for 2000000 ,8.24,6Years using function with return type without arguments.
## ALGORITHAM :
1.Start

2.Define a function calculateEMI with a return type of double to calculate the EMI.

3.Inside the calculateEMI function:

a. Declare variables for principal amount, annual interest rate, loan tenure in years, monthly interest rate, tenure in months, and EMI.

b. Calculate the monthly interest rate by dividing the annual interest rate by 12 and converting it to a decimal.

c. Calculate the loan tenure in months.

d. Use the EMI formula to compute the EMI, incorporating the principal, monthly interest rate, and loan tenure.

e. Return the calculated EMI.

4.In the main function:
a. Call the calculateEMI function to obtain the EMI value and store it in a variable.
b. Print the calculated EMI.

5.End
## PROGRAM :
```
#include<stdio.h>
#include<math.h>
float emi(float x,float y,float
z){y=y/(12*100);
z=z*12;
float isl=x * y *pow((1+y),z) / (pow(1+y,z)-1);
return isl;
}
int main(){
float a=2000000,b=8.24,c=6,emos;
scanf("%f%f%f",&a,&b,&c);
emos=emi(a,b,c);
printf("Monthly EMI is= %.3f",emos);
}
```
## OUTPUT :
![image](https://github.com/Niroshassithanathan/EX-3-A-FUNCTIONS/assets/121418437/f9c7c83c-c4e8-4beb-a5c3-26c499e4d517)

## RESULT :
Thus , The C program has been executed
