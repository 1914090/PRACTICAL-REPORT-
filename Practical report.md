
                     

# **PROGRAMMING FOR PROBLEM SOLVING**

## ESC-18105 
## NAME-*ROHAN SINGH*
## ROLL NO-*1914090*
## BRANCH-*CIVIL*
## SECTION-*CE(B2)*
![LOGO](https://blog.coachingkaro.org/wp-content/uploads/2019/07/logo.jpg)
## **DEPARTMENT OF CIVIL ENGENEERING**
# **GURU NANAK DEV ENGENEERING COLLEGE,LUDHIANA**



------------------------------------------------------------------------------------------------------------------------

# 1.PROGRAM TO PRINT HELLO WORLD
 ```C
       include<stdio.h>
         void main()
         {
         puts("hello world\n");
         }
 ```
        
## OUTPUT OF PROGRAM         
```c         
         hello world
```
--------------------------------------------------------------------------------------------------------------------------------
# 2.PROGRAM TO PRINT MULTIPLICATION TABLE
```c
          #include <stdio.h>
           int main()
           {
           int a, b ;
           printf("enter the number=",a);
           scanf("%d", &a);
           for(int b=1;b<=10;b++)
           {
           printf("%d x %d=%d\n", a, b, a*b);
           }
           return 0;
           }
```
## OUTPUT OF PROGRAM
```c
             enter the number=12
               12 x 1=12
               12 x 2=24
               12 x 3=36
               12 x 4=48
               12 x 5=60
               12 x 6=72
               12 x 7=84
               12 x 8=96
               12 x 9=108
               12 x 10=120
 ```              
 -------------------------------------------------------------------------------------------------------------------------
 
 # 3.PROGRAM TO ADD 2 NUMBERS
 ```c
          #include<stdio.h>
           int main()
          {
          int a, b, c;
          printf("Enter two numbers to add\n"); 
          scanf("%d%d", &a, &b);
          c = a + b;
          printf("Sum of the numbers = %d\n", c);
          return 0;
          }
```
## OUTPUT OF PROGRAM
```c
         Enter two numbers to add
                      12
                      12
         Sum of the numbers = 24
 ```     
 ------------------------------------------------------------------------------------------------------------------------------
 # 4.PROGRAM FOR ARITHMATIC OPERATIONS
 ```c
              #include<stdio.h>
               int main()
              { 
              int a, b, c;
              printf("Enter two numbers\n"); 
              scanf("%d%d", &a, &b);
                c = a + b;
              printf("Sum of the numbers = %d\n", c);
                 c=a-b;
              printf("Diff of 2 numbers=%d\n",c);
                 c=a*b;
              printf("product of 2 numbers=%d\n",c);
              return 0;
              }
```
## OUTPUT OF PROGRAM
```c
           Enter two numbers
               12
               15
           Sum of the numbers = 27
           Diff of 2 numbers=-3
           product of 2 numbers=180
```
----------------------------------------------------------------------------------------------------------------------------------------
# 5.PROGRAM TO PRINT A TO Z
```c
        #include<stdio.h>
         int main()
        {
         char c;
         for(char c='A';c<='Z';c++)
         {
          printf("%c \n",c);
          }
          return 0;
          }
```
## OUTPUT OF PROGRAM
```c
                  A 
                  B 
                  C 
                  D 
                  E 
                  F 
                  G 
                  H 
                  I 
                  J 
                  K 
                  L 
                  M 
                  N 
                  O   
                  P 
                  Q 
                  R 
                  S 
                  T 
                  U 
                  V 
                  W 
                  X 
                  Y 
                  Z
```
--------------------------------------------------------------------------------------------------------------------------------
# 6.PROGRAM TO FIND DIVIDEND AND DIVISOR
```c
       #include <stdio.h>
        double main()
        {
        int a,b;
        double c,d;
        printf("enter dividend=",a);
        scanf("%d",&a);
        printf("enter divisor=",b);
        scanf("%d",&b);
          c=a/b;
        printf("\n quotient=%0.2f\n",c);
          d=a % b;
       printf("reminder=%0.2f\n",d);
       return 0;
       }
 ```      
 ## OUTPUT OF PROGRAM
 ```c
           enter dividend=124
            enter divisor=12

             quotient=10.00
             reminder=4.00
```
-----------------------------------------------------------------------------------------------------------------------------------
# 7.PROGRAM TO CHECK EVEN ODD NUMBER
  ```c
  
         #include<stdio.h>
         int main()
         {
         int a;
         printf("enter the number=", a);
         scanf("%d", &a);
         if (a%2==0)
         printf("number is even\n\n");
         else
         printf("number is odd\n\n");
         return 0;
         }
 ```
 ## OUTPUT OF PROGRAM
 ```c        enter the number=12
         number is even
 ```
 -------------------------------------------------------------------------------------------------------------------------------------- 
 
 # 8.PROGRAM TO FIND MAXIMUM NUMBER
```c        
            
            #include<stdio.h>
             int main ()
             {
             int a,b,ret;
             printf("enter two numbers=",a,b);
             scanf("%d%d",&a,&b);
             if (a>b)
             ret=a;
             else 
             ret=b;
              printf("Anwser=%d\n",ret);
              return ret;
              }
 ```             
## OUTPUT OF PROGRAM 
```c
      enter two numbers=15
                        14
                 Anwser=15
 
 ```
 -----------------------------------------------------------------------------------------------------------------------------------
 
 # 9.PROGRAM TO FIND MINIMUM OF TWO NUMBERS
 ```c             
              
              #include<stdio.h>
               int main ()
              {
               int a,b,ret;
               printf("enter two numbers=",a,b);
               scanf("%d%d",&a,&b);
               if (a<b)
               ret=a;
               else 
               ret=b;
               printf("Anwser=%d\n",ret);
               return ret;
              }
```
## OUTPUT OF PROGRAM
```c
                 enter two numbers=14 
                   200
                  Anwser=14
 ```
 --------------------------------------------------------------------------------------------------------------------------
  
  # 10.PROGRAM TO PRINT CALCULATOR
 ```c               
                
                #include<stdio.h>
                  void main()
                 {
              puts("\n\
                     _______________\n\
                    | 1 | 2 | 3 |   |\n\
                    |___|___|___| + |\n\
                    | 4 | 5 | 6 |   |\n\
                    |___|___|___|___|\n\
                    | 7 | 8 | 9 | - |\n\
                    |___|___|___|___|\n\
                    |     0     | * |\n\
                    |___________|___|\n");
                   }
```
## OUTPUT OF PROGRAM
```c

          _______________
         | 1 | 2 | 3 |   |
         |___|___|___| + |
         | 4 | 5 | 6 |   |
         |___|___|___|___|
         | 7 | 8 | 9 | - |
         |___|___|___|___|
         |     0     | * |
         |___________|___|
         
```
-------------------------------------------------------------------------------------------------------------------

# 11.PROGRAM TO PRINT FACE
```c
              #include<stdio.h>
               void main()
             {
            puts("________________"); 
            puts("|  XXXXXXXXX   |");
            puts("| (  ^    ^ )  |");
            puts("| (  0    0 )  |");
            puts("|  \\    |  /   |");
            puts("|   \\   = /    |");
            puts("|    \\__ /     |");
            puts("|       |      |");
            puts("|_______|______|\n");
            }
 ```           
  ## OUTPUT OF PROGRAM
```c
              ________________
              |  XXXXXXXXX   |
              | (  ^    ^ )  |
              | (  0    0 )  |
              |  \    |  /   |
              |   \   = /    |
              |    \__ /     |
              |       |      |
              |_______|______|
              
```
----------------------------------------------------------------------------------------------------------------------------------

# 12.PROGRAM TO PRINT LINE OF ANY LENGTH
```c  
          #include<stdio.h>
           int main()
           {
           int a;
           printf("enter length of line=");
           scanf("%d",&a);
           for(int  i=1;i<=a;i++)
           {
           printf("_____");
           }
           printf("\n\n");
           return 0;
            }
```
## OUTPUT OF PROGRAM
   ```c              
                 enter length of line=12
                  ____________________________________________________________
```
----------------------------------------------------------------------------------------------------------------------------------------
# 13.PROGRAM TO FIND SUM OF N NATURAL NUMBERS
   ```c      
         #include<stdio.h>
         int main()
         {
         int n,sum;
         printf("enter number=",n);
         scanf("%d",&n);
         sum=n*(n+1)/2;
         printf("\n%d\n\n",sum);
         return 0;
         }
```
## OUTPUT OF PROGRAM
```c
         enter number=12

         78
```
----------------------------------------------------------------------------------------------------------------------------
# 14.PROGRAM TO FIND PERIMETER,AREA AND VOLUME OF RECTANGLE
```c
                #include<stdio.h>
                int main()
               {
                int a,b,c,peri,area,vol;
                printf("enter length,bredth and height of rectangle", a,b,c );
                scanf("%d%d%d",&a ,&b ,&c);
                  peri= 2*(a+b);
                  area=a*b;
                  vol=a*b*c;
                printf("\nperimeter=%d\n\n", peri);
                printf("area=%d\n\n",area); 
                printf("volume=%d\n\n", vol);
                return 0;
                }
```
## OUTPUT OF PROGRAM
```c
                    enter length,bredth and height of rectangle12
                                 14
                                 14

                     perimeter=52

                     area=168 

                     volume=2352
   ```
   ----------------------------------------------------------------------------------------------------------------------------
  # 15.PROGRAM TO FIND PERIMETER ANSD AREA OF CIRCLE
  ```c
             #include<stdio.h>
              int main()
             {
              float a,pi=22/7.0,peri,area;
              printf("enter radius=");
              scanf("%f", &a);
              peri=2*pi*a;
              area=pi*a*a;
              printf("Perimeter of circle=%.2f\n", peri );
              printf("Area=%.2f\n", area);
              return 0;
             } 
 ```
 ## OUTPUT OF PROGRAM
 ```c
      enter radius=7
      Perimeter of circle=44.00
      Area=154.00
```
-----------------------------------------------------------------------------------------------------------------------------------
# 16.PROGRAM TO FIND POWER OF A NUMBER
   ```c      
         #include<stdio.h>
         int main()
         {
         int base,exp;
         int result=1;
         printf("\nEnter base number\n");
         scanf("%d",&base);
         printf("Enter exponent");
         scanf("%d",&exp); 
         while (exp!=0)
         {
         result *=base;
         exp--;
         }
         printf("awnser=%d\n", result);
         return 0;
         }
 ```        
## OUTPUT OF PROGRAM
```c
         Enter base number
         2
         Enter exponent5
         awnser=32
```
-----------------------------------------------------------------------------------------------------------------------------------
# 17.PROGRAM TO CHECK PRIME NUMBER
   ```c     
        
        #include<stdio.h>
         int main()
        {
         int n;

        printf("enter number");
        scanf("%d",&n);

        for(int i=1;i<n;i++)
          {
                if(n%i!=0)
          {  printf("no is prime");
                             break;  }
           else
            {
                printf("no is not prime");
                                    break;  }
                  }

                 return 0;
          }
 ```         
## OUTPUT OF PROGRAM
```c
           enter number15
           no is not prime

```
---------------------------------------------------------------------------------------------------------------------------------------

# 18.PROGRAM TO PRINT NUMBERS USING WHILE LOOP
```c        
        
        #include<stdio.h>
         int main()
       {
         int n=1;

        while(n<=10)
        {
          printf("%d\n",n);
           n++;
          }
        return 0;
         }
  ```
 # OUTPUT OF PROGRAM
```c
                    1
                    2
                    3
                    4
                    5
                    6
                    7
                    8
                    9
                   10
```
--------------------------------------------------------------------------------------------------------------------------------------

# 19.PROGRAM TO PRINT NUMBERS USING DO WHILE LOOP
```c    
     #include<stdio.h>
      int main()
     {
       int i=1;
       do{
          printf("%d\n",i);
           i++;
               }
         while(i<=20);
      return 0;
      }
 ```     
## OUTPUT OF PROGRAM
```c
                      1
                      2
                      3
                      4
                      5
                      6
                      7
                      8
                      9
                      10
                      11
                      12
                      13
                      14
                      15
                      16
                      17
                      18
                      19
                      20
```
----------------------------------------------------------------------------------------------------------------------------------------

# 20.PROGRAM FOR LINEAR SEARCH
```c
     #include<stdio.h>
      int main()
     {
       int sidhant[15]={1,4,48,78,45,12,14,15,20,21,3,5,7,2,9};
       int size=15;
       int flag=0;
       int item,a,i;
       printf("enter number you want to find=");
       scanf("%d",&a);
       for(int i=0;i<size;i++)
    {
        if(a==sidhant[i])
        {
            flag++; 
         }
         }
         if (flag>0){
         printf("\nserach is sucessfull\n");}
         else{
         printf("\nelement not found\n");}
         return 0;
         }
 ```       
 ## OUTPUT OF PROGRAM  
 ```c
       enter number you want to find=12

        serach is sucessfull
      1914109@computer-centre:~/public_html/PPS/Content/Programs/Week02/1914109$ ./a.out 
          enter number you want to find=100

          element not found
```
---------------------------------------------------------------------------------------------------------------------------------
# 21.PROGRAM FOR BINARY SEARCH
```c
       #include <stdio.h>
        int main()
       {
         int a[10],i,s,l,n,f,m=0;
         printf("number of element in array");
         scanf("%d",&n);
         for(i=0;i<n;i++)
         {
         printf("enter [%d] element=",i);
         scanf("%d",&a[i]);
         }
         printf("enter element to be searched");
         scanf("%d",&s);
         f=0;
         l=n-1;
         m=(f+l)/2;
         while(f<=l)
         {
         if(a[m]>s)
         {
         l=m-1;
         }
         else if(a[m]<s)
         {
         f=m+1;
         }
         if (a[m]=s)
         {
         printf("location of given element is %d\n",m);
         break;
         }
         else
         l =m-1;
         m = (f + l)/2;
          }
         if (f > l)
         printf("Not found! %d isn't present in the list.\n", s);
 
         return 0;  
         }
 ```     
  ## OUTPUT OF PROGRAM
 ```c        number of element in array5
         enter [0] element=1
         enter [1] element=2
         enter [2] element=3
         enter [3] element=4
         enter [4] element=5
         enter element to be searched3
         location of given element is 3
```
----------------------------------------------------------------------------------------------------------------------------------
# 22. PROGRAM TO PRINT ODD NUMBERS USING DO WHILE LOOP
   ```c                                                                                                                          } 
       #include<stdio.h>
       int main()
       {
       int a=1,b,c;
       printf("enter number:");
       scanf("%d",&b);
       do{
       if (a%2!=0)
       printf("%d",a);

      else
      printf("\n");
      a++;
      }
      while 
      (a<=b);
      return 0;
      }
```      
      
      
## OUTPUT OF PROGRAM 
```c     
        enter number:15
         1
         3
         5        
         7
         9
         11
         13
         15
```
----------------------------------------------------------------------------------------------------------------------------------------

# 23. PROGRAM TO PRINT EVEN NUMBERS USING DO WHILE LOOP
   ```c
   include<stdio.h>
         int main()
         {
         int a=1,b,c;
         printf("enter number:");
         scanf("%d",&b);
         do{
         if (a%2==0)
         printf("%d",a);
         else
         printf("\n");
         a++;
         }
         while
         (a<=b);
         return 0;
         }
```
## OUTPUT OF PROGRAM
   ```c      enter number:15
         2
         4
         6
         8
         10
         12
         14
```
-------------------------------------------------------------------------------------------------------------------------------------
# 24. PROGRAM OF CALCULATOR USING CASE SWITCH STATEMENT
   ```c
         #include<stdio.h>
         int main()
         {
         int a,b,c,d;
         printf("Enter 1 addition.2 subtraction,3 multiplication,4 division");
         scanf("%d",&a);
         switch(a)
         {
         case 1:; if(a=1)
         {
         printf("enter two numbers");
         scanf("%d%d",&b,&c);
         d=b+c;
         printf("sum=%d",d);
         break;
         }
         case 2: if(a=2)
         {
         printf("enter two numbers");
         scanf("%d%d",&b,&c);
         d=b-c; 
         printf("diffrence=%d",d); 
         break;
         }
         case 3: if(a=3) 
         {
         printf("enter two numbers");
         scanf("%d%d",&b,&c);
         d=b*c;
         printf("product=%d",d); 
         break;
         }
         case 4:if(a=4)
         {
         printf("enter two numbers");
         scanf("%d%d",&b,&c);
         d=b/c;
         printf("quotient=%d",d); 
         break;   
         }
         default:
         printf("sorry");
         }
         return 0;
         }
```
## OUTPUT OF PROGRAM
```c
         Enter 1 addition.2 subtraction,3 multiplication,4 division2
                  enter two numbers15
                           1
                    diffrence=14
```
------------------------------------------------------------------------------------------------------------------------------------
# 25. PROGRAM TO FIND AVERAGE OF N NUIMBERS
```c         
         #include<stdio.h>
         int main()
         {

         float a,b,sum=0;
         float c;
         printf("enter number");
         scanf("%f",&a);
         for(b=1;b<=a;b++)
         {
         sum+=b;  
         }
         c=sum/a;
         printf("average=%0.3f",c);

         return 0;
         }
```
## OUTPUT OF PROGRAM
   ```c    
         enter number14
         average=7.500
 ```
 -------------------------------------------------------------------------------------------------------------------------------------
#  26. PROGRAM TO SWAP TWO NUMBERS USING CALL BY VALUE
```c
         #include <stdio.h>
         int main()
         {
         int x, y, t;
      printf("\n\nEnter two integers: ");
      scanf("%d %d", &x, &y);
      printf("\n\nBefore Swapping: \nFirst integer = %d\nSecond integer = %d\n", x, y);
      t = x;
      x = y;
      y = t;
      printf("\n\nAfter Swapping: \nFirst integer = %d\nSecond integer = %d\n", x, y);
      return 0;
    }

```
## OUTPUT OF PROGRAM
```c
    Enter two integers: 2050

    Before Swapping:
    First integer = 2
    Second integer = 50
     
    After swapping
    First integer = 50
    Second integer = 2
```
--------------------------------------------------------------------------------------------------------------------------------
# 27. PROGRAM TO FIND FACTORIAL OF A NUMBER
   ```c
          #include<stdio.h>
         int main()
         {
         int a, b=1, c;
         printf("Enter  number \n"); 
         scanf("%d", &a); 
         for(int i=1;i<=a;i++)
         {
         b*=i;
         }
         printf("factorial=%d\n", b);
         return 0;
         }
```
## OUTPUT OF PROGRAM
   ```c
        enter  number 
         3
         factorial=6
```
-----------------------------------------------------------------------------------------------------------------------------------
# 28.PROGRAM FOR BUBBLE SORTING
 ```c
     #include<stdio.h>
         int main()
         {
         int a[5],i,j,k;
         printf("Enter elements of an aaray=\n");
         for(int c=0;c<5;c++)
         {
         scanf("%d",&a[c]);
         }
         printf("output");
         for(i=0;i<5;i++)
         {
         for(j=i+1;j<5;j++)
         {
         if(a[i]>a[j])
         {
         k=a[i];
         a[i]=a[j];
         a[j]=k;
         }}}
         for(i=0;i<5;i++)
         printf("%d\n",a[i]);
         return 0;
         }
```
## OUTPUT OF PROGRAM
   ```c 
        Enter elements of an aaray=
         1
         14
         2
         3
         4
         output
         1
         2
         3
         4
         14
```
---------------------------------------------------------------------------------------------------------------------------------------         
# 29.PROGRAM FOR MATRIX MULTIPLICATION
```c
         #include<stdio.h>
         int main()
         {
         int a,b,c,d,e,f,g,h,i,j,k,l,m,n,o,p,q,r,A,B,C,D,E,F,G,H,I;
         printf("enter first matrix:\n");
         scanf("%d%d%d%d%d%d%d%d%d\n" ,&a,&b,&c,&d,&e,&f,&g,&h,&i );
         printf("enter second matrix:\n");
         scanf("%d%d%d%d%d%d%d%d%d\n",&j,&k,&l,&m,&n,&o,&p,&q,&r);
         A=a*j+b*m+c*p;
         B=a*k+b*n+c*q;
         C=a*l+b*o+c*r;
         D=d*j+e*m+f*p;
         E=d*k+e*n+f*q;
         F=d*l+e*o+f*r;
         G=g*j+h*m+i*p;
         H=g*k+h*n+i*q;
         I=g*l+h*o+i*r;
         printf("\n\nResultant matrix:\n\n");
         printf("\n\n|%d  %d  %d |\n",A,B,C);
         printf("|%d  %d  %d |\n",D,E,F);
         printf("|%d  %d  %d |\n\n",G,H,I);
         return 0;
         }
```
## OUTPUT OF PROGRAM
```c
        enter first matrix:
         1
         1
         1
         1
         1
         1
         1
         1
         1
         1
         enter second matrix:
         1
         1
         1
         1
         1
         1
         1
         1
         1


         Resultant matrix:



         |3  3  3 |
         |3  3  3 |
         |3  3  3 |
```
---------------------------------------------------------------------------------------------------------------------------------------         
# 30.PROGRAM FOR QUICK SORT USING RECURSION

```c
      #include<stdio.h>
       void quicksort(int[],int,int);
       int main()
      {
       int list [50];
       int size,i;
       printf("enter no of elements");
       scanf("%d",&size);
       for(i=0;i<size;i++)
      {
       scanf("%d",&list[i]);
      }
       quicksort(list,0,size-1);
       printf("after applying sort");
       for(i=0;i<size;i++)
      {
       printf("%d",list[i]);
      }
       printf("\n");
       return 0;
      }
       void quicksort(int list[],int low,int high)
      {
       int pivot,i,j,temp;
       if(low<high)
      {
       pivot=low;
       i=low;
       j=high;
       while(i<j)
      {
       while(list[i]<=list[pivot]&&i<=high)
      {
      i++;
      }
       while(list[j]>list[pivot]&&j>=low)
      {
       j--;
      }
       if(i<j)
      {
       temp=list[i];
       list[i]=list[j];
       list[j]=temp;
      }
      }
       temp=list[j];
       list[j]=list[pivot];
       list[pivot]=temp;
       quicksort(list,low,j-1);
       quicksort(list,j+1,high);
      }
      }
```
      
## OUTPUT OF PROGRAM
 ```c
       1914109@computer-centre:~/public_html/PPS/Content/Programs/Week02/1914109$ ./a.out 
       enter no of elements5
                     12
                     4
                     23
                     14
                      2
        after applying sort2
                     4
                    12
                    14
                    23
```
---------------------------------------------------------------------------------------------------------------------------------------              
# 31.PROGRAM TO PRINT FIBBONACCI SERIES

```C 
        #include<stdio.h>
 
        int Fibonacci(int);
 
        int main()  
        { 
        int n, i = 0, c;
 
        scanf("%d",&n);
 
        printf("Fibonacci series\n");
 
        for ( c = 1 ; c <= n ; c++ ) { 
        printf("%d\n", Fibonacci(i)); i++;
       }
 
        return 0;
       }
 
        int Fibonacci(int n) { if ( n == 0 ) return 0; 
        else if ( n == 1 )
        return 1; else return ( Fibonacci(n-1) + 
        Fibonacci(n-2) );
       }
```
## OUTPUT OF PROGRAM
```C       
           1914109@computer-centre:~/public_html/PPS/Content/Programs/Week02/1914109$ ./a.out 
             12
           Fibonacci series
               0
               1
               1
               2
               3
               5
               8
               13
               21
               34
               55
               89
```
----------------------------------------------------------------------------------------------------------------------------------             
