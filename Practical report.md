
                     
# **PROGRAMMING FOR PROGRAM SOLVING ESC-18105**
## NAME-*ROHAN SINGH*
## ROLL NO-*1914090*
## BRANCH-*CIVIL*
## SECTION-*CE(B2)*
![LOGO](https://blog.coachingkaro.org/wp-content/uploads/2019/07/logo.jpg)
## **DEPARTMENT OF CIVIL ENGENEERING**
# **GURU NANAK DEV ENGENEERING COLLEGE,LUDHIANA**
# 1. Program to print Hello World
#include<stdio.h>
void main()
{
puts("\nHello World\n");
}
## Output of the program
Hello World
# 2. Program to find Sum
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
# 3. Program to print a Table
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
73.00 x 6 = 438.000#include<stdio.h>
int main()
{
float r,P,A,V;
float pi = 22/7.0;
printf("\nEnter The Radius of Circle: ");
scanf("%f",&r);
P = 2*pi*r;
A = pi*r*r;
V = 4*pi*r*r*r/3.0;
printf("\nPerimeter of Circle is: = %.2f",P);
printf("\nArea of Circle is: = %.2f",A);
printf("\nVolume of Circle is: = %.2f",V);
return 0;
}
## Output of the program
Enter The Radius of Circle: 4.5
Perimeter of Circle is: = 28.29
Area of Circle is: = 63.64
Volume of Circle is: = 381.86
# 5. Program to find Area, Perimeter of a Rectangle
#include<stdio.h>
int main()
{
float h,b,A,P;
printf("\nEnter Height: ");
scanf("%f",&h);
printf("\nEnter Bredth: ");
scanf("%f",&b);
73.00 x 7 = 511.000
# 4. Program to find Area, Perieter, Volume of a Circle
