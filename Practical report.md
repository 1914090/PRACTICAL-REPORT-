
                     
# **PROGRAMMING FOR PROGRAM SOLVING ESC-18104/18105**
## NAME-*ROHAN SINGH*
## ROLL NO-*1914090*
## BRANCH-*CIVIL*
## SECTION-*CE(B2)*
![LOGO](https://blog.coachingkaro.org/wp-content/uploads/2019/07/logo.jpg)
## **DEPARTMENT OF CIVIL ENGENEERING**
# **GURU NANAK DEV ENGENEERING COLLEGE,LUDHIANA**


# 1. Program to print a Table
#include<stdio.h>
int main()
{
float x;
int n;
printf("\nEnter The Table: ");
scanf("%f",&x);
printf("\nEnter No. Times: ");
scanf("%d",&n);
for(int y=1; y<=n; y++)
{
printf("\n%.2f x %d = %.3f",x,y,x*y);
}
return 0;
}
## Output of the program
73.00 x 1 = 73.000
73.00 x 2 = 146.000
73.00 x 3 = 219.000
73.00 x 4 = 292.000
73.00 x 5 = 365.000
73.00 x 6 = 438.000
73.00 x 7 = 511.000

# 2. Program to print Hello World
#include<stdio.h>
void main()
{
puts("\nHello World\n");
}
## Output of the program
Hello World

# 3. Program to find Sum
#include<stdio.h>
int main()
{
float x,y,z;
printf("\nEnter The First Numder: ");
scanf("%f", &x);
printf("\nEnter The Second Numder: ");
scanf("%f", &y);
z = x+y;
printf("\nAnswer is: = %.3f", z);
return 0;
}
## Output of the program
Enter The First Numder: 45.26
Enter The Second Numder: 78.2648
Answer is: = 123.525


# 8. Program of Sum of two Constants
#include<stdio.h>
int main()
{
int a=100,b=120,c;
c = a+b;
printf("\na=100\nb=120\nSum of a and b is :%d",c);
return 0;
}
## Output of the program
a=100
b=120
Sum of a and b is :220


