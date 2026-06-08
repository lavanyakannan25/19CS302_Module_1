# EX 5 C Write a C program to find compound interest. Note: Inputs are principle, year and rate.
## DATE:
## AIM:
Write a C program to find compound interest. 

## Algorithm
1. Start. 
2. Declare three variable value of type int for marks.
3. Prompt the user to enter a value.
4. Read the value using scanf. 
5. Find total and average.
6. Print the result
7. End.  

## Program:
```
 
#include <stdio.h>
#include<math.h>
int main()
{
   float p,y,r,c;
   scanf("%f%f%f",&p,&y,&r);
   c=p*(pow((1+r/100),y));
   printf("Amount with Compound Interest = %.2f",c);
   return 0;
}
```

## Output:

<img width="1627" height="403" alt="Screenshot (54)" src="https://github.com/user-attachments/assets/7fbca597-daa7-419e-b83b-29ac3875eca0" />


## Result:
Thus the program was executed and the output was verified successfully.
