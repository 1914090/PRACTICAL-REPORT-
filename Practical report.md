
                     
# **PROGRAMMING FOR PROGRAM SOLVING ESC-18104/18105**
## NAME-**_ROHAN SINGH_**
## ROLL NO-**_1914090_**
## BRANCH-**_CIVIL_**
## SECTION-**_CE(B2)_**
![LOGO](https://blog.coachingkaro.org/wp-content/uploads/2019/07/logo.jpg)
## **DEPARTMENT OF CIVIL ENGENEERING**
# **GURU NANAK DEV ENGENEERING COLLEGE,LUDHIANA**


# 1. Program to print Hello World
```C
#include<stdio.h>
void main()
{
puts("\nHello World\n");
}
```
## Output of the program
Hello World


# 2. Program to find Sum
```C
#include<stdio.h>
int main()
{
float x,y,z;
printf("\nEnter The First Number: ");
scanf("%f", &x);
printf("\nEnter The Second Number: ");
scanf("%f", &y);
z = x+y;
printf("\nAnswer is: = %.3f", z);
return 0;
}
```

## Output of the program
Enter The First Numder: 45.26
Enter The Second Numder: 78.2648
Answer is: = 123.525

# 3. Program to print a Table
```C
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
```
## Output of the program
73.00 x 1 = 73.000
73.00 x 2 = 146.000
73.00 x 3 = 219.000
73.00 x 4 = 292.000
73.00 x 5 = 365.000
73.00 x 6 = 438.000
73.00 x 7 = 511.000


# 4. Program to find Maximum
```C
#include<stdio.h>
int max(float x,float y);
int main()
{
float x,y,z;
printf("\nEnter The First Value: ");
scanf("%f",&x);
printf("\nEnter The Second Value: ");
scanf("%f",&y);
z = max(x,y);
printf("\nMaximum value is: %.2f\n", z);
return 0;
}
int max(float x,float y)
{
float result;
if(x<y)
result = y;
else
result = x;
return result;
}
```
## Output of the program
Enter The First Value: 5
Enter The Second Value: 4
Maximum value is: 5.00

# 5. Program of Sum of two Constants
```C
#include<stdio.h>
int main()
{
int a=100,b=120,c;
c = a+b;
printf("\na=100\nb=120\nSum of a and b is :%d",c);
return 0;
}
```
## Output of the program
a=100
b=120
Sum of a and b is :220

# 6. Program To find Minimum
```C
#include<stdio.h>
int min(float x,float y);
int main()
{
float x,y,z;
printf("\nEnter The First Value: ");
scanf("%f",&x);
printf("\nEnter The SecondValue: ");
scanf("%f",&y);
z = min(x,y);
printf("\nMinimum value is: %.2f\n", z);
return 0;
}
int min(float x,float y)
{
float result;
if(x<y)
result = x;
else
result = y;
return result;
}
```
## Output of the program
Enter The First Value: 5
Enter The SecondValue: 3
Minimum value is: 3.00

# 7. Program to print Bio Data of Students
```C
#include<stdio.h>
int main()
{
int n,R;
char name[25];
printf("\nEnter The Number of Students: ");
scanf("%d",&n);
for(int i=1; i<=n;i++)
{
printf("\nEnter The Name of The Student : ");
scanf("%s", name);
printf("Enter The Roll No. of Students: ");
scanf("%d",&R);printf("\nName = %s\nRoll No. = %d\n", name,R);
}
return 0;
}
```
## Output of the program
Enter The Number of Students: 3
Enter The Name of The Student : Sharan
Enter The Roll No. of Students: 1914103
Name = Sharan
Roll No. = 1914103
Enter The Name of The Student : Sidhant
Enter The Roll No. of Students: 1914109
Name = Sidhant
Roll No. = 1914109
Enter The Name of The Student : Rohan
Enter The Roll No. of Students: 1914090
Name = Rohan
Roll No. = 1914090

# 8. Program to use Arithmetic Operators
```C
#include<stdio.h>
int main()
{
float x,y,a;
printf("\nEnter The Value of x: ");
scanf("%f",&x);
printf("\nEnter The Value of y: ");
scanf("%f",&y);
a = x+y;printf("x + y = %.3f\n",a);
a = x-y;
printf("x - y = %.3f\n",a);
a = y-x;
printf("y - x = %.3f\n",a);
a = x*y;
printf("x * y = %.3f\n",a);
a = x/y;
printf("x/y = %.3f\n",a);
a = y/x;
printf("y/x = %.3f\n",a);
return 0;
}
```
## Output of the program
Enter The Value of x: 45
Enter The Value of y: 31
x + y = 76.000
x - y = 14.000
y - x = -14.000
x * y = 1395.000
x/y = 1.452
y/x = 0.689
# 9. Program to use Assignment Operators
```C
#include<stdio.h>
int main()
{
float x,a;
printf("\nEnter The Value of x: ");
scanf("%f",&x);
a = x;
printf("Answer is a = x %.3f\n",a);
a +=x; //answer is a+x
printf("Answer is a+x = %.3f\n",a);
a -=x; //answer is a-x
printf("Answer is a-x = %.3f\n",a);
a *=x; //answer is a*x
printf("Answer is a*x = %.3f\n",a);
a /=x; //answer is a/x
printf("Answer is a/x= %.3f\n",a);
return 0;
}
```
## Output of the program
Enter The Value of x: 45
Answer is a = x 45.000
Answer is a+x = 90.000
Answer is a-x = 45.000
Answer is a*x = 2025.000
Answer is a/x= 45.000
# 10. Program to use Operator Precedence
```C
#include<stdio.h>
int main()
{
float a,b,c,d,A;
printf("\nEnter The Value of a: ");
scanf("%f",&a);
printf("Enter The Value of b: ");
scanf("%f",&b);
printf("Enter The Value of c: ");
scanf("%f",&c);
printf("Enter The Value of d: ");
scanf("%f",&d);
A = (a+b)*(c+d);
printf("\n (a+b)*(c+d) = %.3f",A);
A = (c+d)*a*b;
printf("\n (c+d)*a*b = %.3f",A);
A = a*d/(c-b-a);
printf("\n a*d/(c-b-a) = %.3f",A);
A = (b-c)*(a-d);
printf("\n (b-c)*(a-d) = %.3f",A);
return 0;
}
```
## Output of the program
Enter The Value of a: 45
Enter The Value of b: 31
Enter The Value of c: 18
Enter The Value of d: 71
(a+b)*(c+d) = 6764.000
(c+d)*a*b = 124155.000
a*d/(c-b-a) = -55.086
(b-c)*(a-d) = -338.000
# 11. Program to find Average
```C
#include<stdio.h>
float average();
int main()
{
printf("\nAverage is: %.2f",average());
return 0;
}
float average()
{
float x,y,z,s,a;
printf("\nEnter The First Value: ");
scanf("%f",&x);
printf("Enter The Second Value: ");
scanf("%f",&y);
printf("Enter The Third Value: ");
scanf("%f",&z);
s = x+y+z;
a = s/3;
return a;
}
```
## Output of the program
Enter The First Value: 45
Enter The Second Value: 34
Enter The Third Value: 18
Average is: 32.33

# 12. Program to find FizzBuzz of a Integer
```C
#include<stdio.h>
int main()
{
int n;
printf("\nEnter the Interger: ");
scanf("%d",&n);
if(n%15==0)
printf("\nFizzBuzz");
else if(n%3==0)
printf("Fizz\n");
else if (n%5==0)
printf("\nBuzz");
else
printf("\n%d",n);
return 0;
}
```
## Output of the program
Enter the Interger: 171
Fizz
# 13. Program of print a Calculator using puts function
```C
#include<stdio.h>
void main()
{
puts("\n\
_______________\n\
| 1 | 2 | 3 | |\n\
|___|___|___| |\n\
| 4 | 5 | 6 | + |\n\
|___|___|___|___|\n\
| 7 | 8 | 9 | - |\n\
|___|___|___|___|\n\
| 0 | * |\n\
|___________|___|\n");
}
```
## Output of the program
_______________
| 1 | 2 | 3 | |
|___|___|___| |
| 4 | 5 | 6 | + |
|___|___|___|___|
| 7 | 8 | 9 | - |
|___|___|___|___|
| 0 | * |
|___________|___|

# 14. Program of Addition of 2x2 Matrix
```C
#include<stdio.h>
int main()
{
float a,b,c,d,e,f,g,h,i,j,k,l;
printf("\nSample of Ist matrix: | a=1 b=2 |\n | c=3 d=4 |\n\n\
Sample of 2nd matrix: | e=5 f=6 |\n | f=7 h=8 |\n\n");
printf("Enter The Valve of a: ");
scanf("%f",&a);
printf("Enter The Valve of b: ");
scanf("%f",&b);
printf("Enter The Valve of c: ");
scanf("%f",&c);
printf("Enter The Valve of d: ");
scanf("%f",&d);
printf("Enter The Valve of e: ");
scanf("%f",&e);
printf("Enter The Valve of f: ");
scanf("%f",&f);
printf("Enter The Valve of g: ");
scanf("%f",&g);
printf("Enter The Valve of h: ");
scanf("%f",&h);
i = a+e;
j = b+f;
k = c+g;
l = d+h;
printf("\n\nSum of Matrix(A+B) is: | %.2f %.2f |\n | %.2f %.2f |",i,j,k,l);
i = a-e;
j = b-f;
k = c-g;
l = d-h;
printf("\n\nSubstraction of Matrix(A-B) is: | %.2f %.2f |\n | %.2f
%.2f |",i,j,k,l);
i = e-a;
j = f-b;
k = g-c;
l = h-d;


printf("\n\nSubstraction of Matrix(B-A) is: | %.2f %.2f |\n | %.2f
%.2f |",i,j,k,l);
return 0;
}
```
## Output of the program
Sample of Ist matrix: | a=1 b=2 |
| c=3 d=4 |
Sample of 2nd matrix: | e=5 f=6 |
| f=7 h=8 |
Enter The Valve of a: 7
Enter The Valve of b: 5
Enter The Valve of c: 4
Enter The Valve of d: 0
Enter The Valve of e: 3
Enter The Valve of f: 5
Enter The Valve of g: 9
Enter The Valve of h: 1
Sum of Matrix(A+B) is: | 10.00 10.00 |
| 13.00 1.00 |
Substraction of Matrix(A-B) is: | 4.00 0.00 |
| -5.00 -1.00 |
Substraction of Matrix(B-A) is: | -4.00 0.00 |
| 5.00 1.00 |


# 15. Program of FizzBuzz in a continues loop
```C
#include<stdio.h>
int main()
{
int n,x;
printf("\nEnter The Integer: ");
scanf("%d",&n);
printf("\n");
{
for(x=1;x<=n;x++)
if(x%15==0)
printf("FizzBuzz\n");
else if(x%3==0)
printf("Fizz\n");
else if(x%5==0)
printf("Buzz\n");
else
printf("%d\n",x);
}
return 0;
}
```
## Output of the program
Enter The Integer: 17
1
2
Fizz
4
Buzz
Fizz
7
8Fizz
Buzz
11
Fizz
13
14
FizzBuzz
16
17


# 16.Program of prime number
```C
include <stdio.h>
int main()  
                                                    {
   int n;
printf("enter the number");
scanf("%d",&n);

for(int i=1;i<n;i++)
{
  if(n%i!=0)
    {  
     printf("number is prime");
       break; 
  }
else                                                            {  printf("number is not prime");
   break;  }
}
return 0;
}
```
## Output of the program
enter the number6
number is not prime

# 17.Program to find number is odd or even
```C
#include <stdio.h>

int main()

{

 int n;

 printf("Enter an integer\n");                             
 scanf("%d",&n);

 if ( n%2 == 0 )

 printf("Even\n");

 else

 printf("Odd\n");

 return 0;
}
```

## Output of the program
Enter an integer
13
Odd

# 18.Program of binary search
```C
#include<stdio.h>
int main()
{
        int m,n,a[100],search,first,last,middle;
        printf("Enter the size of array");
        scanf("%d",&m);

        printf("Enter %d number\n",m);

        for(n=0;n<m;n++)
                scanf("%d",&a[n]);
        printf("Enter the the number u want to search\n");
        scanf("%d",&search);
        first=0;
        last=m-1;
        middle=(first+last)/2;

        while(first<=last)
        {
                if(a[middle]<search)
                        first=middle+1;
                else if(a[middle]==search)
                {
                        printf("%d found at location %d\n",search,middle+1);
                        break;
                }
                else
                        last=middle-1;
                middle=(first+last)/2;
        }
        if(first>last)
                printf("Not found! %d is not present in the list \n",search);
        return 0;
}
```
## Output of the program
Enter the size of array7
Enter 7 number
45
57
9
3
5
2
8
Enter the the number u want to search
2
Not found! 2 is not present in the list

# 19.Program of linear search
```C
#include<stdio.h>

int check(int b[],int m,int o)
{int p=-1;
        for(int i=1;i<=m;i++)
        {
                if(b[i]==o)
                 p = i;
        }

                        return p;
        
}

void main()
{
        int n,num,index;
        printf("enter the array size\n");
        scanf("%d",&n);
        int a[n];
        printf("enter the array elements\n");
        for(int i=1;i<=n;i++)
        {
                scanf("%d",&a[i]);
        }
        printf("now enter the number which you want to check\n whether it is present or not in entered array\n");

        scanf("%d",&num);
        index=check(a,n,num);
        if(index==-1)
        printf("element is not found\n");
        else
        printf("element is found at the position %d \n",index);
}
```

## Output of the program
enter the array size
4
enter the array elements
2
3
6
9
now enter the number which you want to check
 whether it is present or not in entered array
6
element is found at the position 3
