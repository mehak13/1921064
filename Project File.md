#**PROGRAMMING FOR PROGRAM SOLVING ESC-18105**
## NAME-*Mehak Gupta *
## ROLL NO-*1921064*
## BRANCH-*IT*
## SECTION-*IT(B1)*
![LOGO](https://blog.coachingkaro.org/wp-content/uploads/2019/07/logo.jpg)
# **DEPARTMENT OF IT ENGENEERING**
# **GURU NANAK DEV ENGENEERING COLLEGE,LUDHIANA**
# 1. Program to print Hello World
#include<stdio.h>\
void main()\
{puts("\nHello World\n");}
## Output of the program
 Hello World
# 2. Program to find Sum
#include<stdio.h>\
int main()\
{float x,y,z;\
printf("\nEnter The First Number: ");\
scanf("%f", &x);\
printf("\nEnter The Second Number: ");\
scanf("%f", &y);\
z = x+y;\
printf("\nAnswer is: = %.3f", z);
\return 0;}
## Output of the program
Enter The First Number: 45.26\
Enter The Second Number: 78.2648\
Answer is: = 123.525\
# 3. Program to print a Table
#include<stdio.h>\
int main()\
{float x;\
int n;\
printf("\nEnter The Table: ");\
scanf("%f",&x);\
printf("\nEnter No. Times: ");\
scanf("%d",&n);\
for(int y=1; y<=n; y++)\
{printf("\n%.2f x %d = %.3f",x,y,x*y);}\
return 0;}
## Output of the program
73.00 x 1 = 73.000\
73.00 x 2 = 146.000\
73.00 x 3 = 219.000\
73.00 x 4 = 292.000\
73.00 x 5 = 365.000\
73.00 x 6 = 438.000\
73.00 x 7 = 511.000
# 4. Program to find Area, Perimeter, Volume of a Circle
#include<stdio.h>\
int main()\
{float r,P,A,V;\
float pi = 22/7.0;\
printf("\nEnter The Radius of Circle: ");\
scanf("%f",&r);\
P = 2*pi*r;\
A = pi*r*r;\
V = 4*pi*r*r*r/3.0;\
printf("\nPerimeter of Circle is: = %.2f",P);\
printf("\nArea of Circle is: = %.2f",A);\
printf("\nVolume of Circle is: = %.2f",V);\
return 0;}
## Output of the program
Enter The Radius of Circle: 4.5\
Perimeter of Circle is: = 28.29\
Area of Circle is: = 63.64\
Volume of Circle is: = 381.86
# 5. Program to find Area, Perimeter of a Rectangle
#include<stdio.h>\
int main()\
{float h,b,A,P;\
printf("\nEnter Height: ");\
scanf("%f",&h);\
printf("\nEnter Breadth: ");\
scanf("%f",&b);\
A = h*b;\
P = 2*(h+b);\
printf("\nArea of Square (or) Rectangle: = %.3f",A);\
printf("\nPerimeter of Sqare (or) Rectangle: = %.3f",P);\
return 0;}
## Output of the program
Enter Height: 24\
Enter Bredth: 60\
Area of Square (or) Rectangle: = 1440.000\
Perimeter of Square (or) Rectangle: = 168.000
# 6. Program to find Interest
#include<stdio.h>\
int main()\
{float P,R,T,Interest;\
printf("\nEnter The Principal Amount: ");\
scanf("%f", &P);\
printf("\nEnter The Interest Rate: ");\
scanf("%f", &R);\
printf("\nEnter The Time (in months): ");\
scanf("%f", &T);\
Interest = P*T*R/100;\
printf("\nSimple Intesest is: = %.2f", Interest);\
return Interest;}
## Output of the program
Enter The Principal Amount: 4000\
Enter The Interest Rate: 4\
Enter The Time (in months): 3\
Simple Intesest is: = 480.00
# 7. Program to find Maximum
#include<stdio.h>\
int max(float x,float y);\
int main()\
{float x,y,z;\
printf("\nEnter The First Value: ");\
scanf("%f",&x);\
printf("\nEnter The Second Value: ");\
scanf("%f",&y);\
z = max(x,y);\
printf("\nMaximum value is: %.2f\n", z);\
return 0;}\
int max(float x,float y)\
{float result;\
if(x<y)\
result = y;\
elseresult = x;\
return result;}
## Output of the program
Enter The First Value: 5\
Enter The Second Value: 4\
Maximum value is: 5.00
# 8. Program of Sum of two Constants
#include<stdio.h>\
int main()\
{int a=100,b=120,c;\
c = a+b;\
printf("\na=100\nb=120\nSum of a and b is :%d",c);\
return 0;}
## Output of the program
a=100\
b=120\
Sum of a and b is :220
# 9. Program To find Minimum
#include<stdio.h>\
int min(float x,float y);\
int main()\
{float x,y,z;\
printf("\nEnter The First Value: ");\
scanf("%f",&x);\
printf("\nEnter The SecondValue: ");\
scanf("%f",&y);\
z = min(x,y);\
printf("\nMinimum value is: %.2f\n", z);\
return 0;}\
int min(float x,float y)\
{float result;\
if(x<y)\
result = x;\
elseresult = y;\
return result;}
## Output of the program
Enter The First Value: 7\
Enter The SecondValue: 3\
Minimum value is: 3.00
# 10. Program to print Bio Data of Students
#include<stdio.h>\
int main()\
{int n,R;\
char name[25];\
printf("\nEnter The Number of Students: ");\
scanf("%d",&n);\
for(int i=1; i<=n;i++)\
{printf("\nEnter The Name of The Student : ");\
scanf("%s", name);\
printf("Enter The Roll No. of Students: ");\
scanf("%d",&R);
printf("\nName = %s\nRoll No. = %d\n", name,R);}\
return 0;}
## Output of the program
Enter The Number of Students: 3\
Enter The Name of The Student : Sharan\
Enter The Roll No. of Students: 1914103\
Name = Sharan\
Roll No. = 1914103\
Enter The Name of The Student : Sidhant\
Enter The Roll No. of Students: 1914109\
Name = Sidhant\
Roll No. = 1914109\
Enter The Name of The Student : Rohan\
Enter The Roll No. of Students: 1914090\
Name = Rohan\
Roll No. = 1914090
# 11. Program to use Arithmetic Operators
#include<stdio.h>\
int main()\
{float x,y,a;\
printf("\nEnter The Value of x: ");\
scanf("%f",&x);\
printf("\nEnter The Value of y: ");\
scanf("%f",&y);\
a = x+y;
printf("x + y = %.3f\n",a);\
a = x-y;\
printf("x - y = %.3f\n",a);\
a = y-x;\
printf("y - x = %.3f\n",a);\
a = x*y;\
printf("x * y = %.3f\n",a);\
a = x/y;\
printf("x/y = %.3f\n",a);\
a = y/x;\
printf("y/x = %.3f\n",a);\
return 0;}
## Output of the program
Enter The Value of x: 45\
Enter The Value of y: 31\
x + y = 76.000\
x - y = 14.000\
y - x = -14.000\
x * y = 1395.000\
x/y = 1.452\
y/x = 0.689
# 12. Program to use Assignment Operators
#include<stdio.h>\
int main()\
{float x,a;\
printf("\nEnter The Value of x: ");\
scanf("%f",&x);\
a = x;\
printf("Answer is a = x %.3f\n",a);\
a +=x;\
//answer is a+x\
printf("Answer is a+x = %.3f\n",a);\
a -=x;\
//answer is a-x\
printf("Answer is a-x = %.3f\n",a);\
a *=x;
//answer is a*x\
printf("Answer is a*x = %.3f\n",a);\
a /=x;\
//answer is a/x\
printf("Answer is a/x= %.3f\n",a);\
return 0;}
## Output of the program
Enter The Value of x: 45\
Answer is a = x 45.000\
Answer is a+x = 90.000\
Answer is a-x = 45.000\
Answer is a*x = 2025.000\
Answer is a/x= 45.000
# 13. Program to use Operator Precedence
#include<stdio.h>\
int main()\
{float a,b,c,d,A;\
printf("\nEnter The Value of a: ");\
scanf("%f",&a);\
printf("Enter The Value of b: ");\
scanf("%f",&b);\
printf("Enter The Value of c: ");\
scanf("%f",&c);\
printf("Enter The Value of d: ");\
scanf("%f",&d);\
A = (a+b)*(c+d);\
printf("\n (a+b)*(c+d) = %.3f",A);\
A = (c+d)*a*b;
printf("\n (c+d)*a*b = %.3f",A);\
A = a*d/(c-b-a);\
printf("\n a*d/(c-b-a) = %.3f",A);\
A = (b-c)*(a-d);\
printf("\n (b-c)*(a-d) = %.3f",A);\
return 0;}
## Output of the program
Enter The Value of a: 45\
Enter The Value of b: 31\
Enter The Value of c: 18\
Enter The Value of d: 71\
(a+b)*(c+d) = 6764.000\
(c+d)*a*b = 124155.000\
a*d/(c-b-a) = -55.086\
(b-c)*(a-d) = -338.000
# 14. Program to find Average
#include<stdio.h>\
float average();\
int main()\
{printf("\nAverage is: %.2f",average());\
return 0;}\
float average()\
{float x,y,z,s,a;\
printf("\nEnter The First Value: ");\
scanf("%f",&x);\
printf("Enter The Second Value: ");\
scanf("%f",&y);
printf("Enter The Third Value: ");\
scanf("%f",&z);\
s = x+y+z;\
a = s/3;\
return a;}
## Output of the program\
Enter The First Value: 45\
Enter The Second Value: 34\
Enter The Third Value: 18\
Average is: 32.33\
# 15. Program to print F by using #
#include<stdio.h>\
int main()\
{printf("\n########\n#\n#\n#\n#####\n#\n#\n#\n#\n#\n#\n");\
return 0;}\
## Output of the program
#########\
#\
#\
#####\
#\
#\
#\
#\
#\
#\
# 16. Program to find FizzBuzz od a Integer
#include<stdio.h>\
int main()\
{int n;\
printf("\nEnter the Interger: ");\
scanf("%d",&n);\
if(n%15==0)\
printf("\nFizzBuzz");\
else if(n%3==0)\
printf("Fizz\n");\
else if (n%5==0)\
printf("\nBuzz");\
else\
printf("\n%d",n);\
return 0;}
## Output of the program
Enter the Interger: 171\
Fizz
# 17. Program of print a Calculator using puts function
#include<stdio.h>\
void main()\
{puts("\n\_______________\n\| 1 | 2 | 3 | |\n\|___|___|___| |\n\| 4 | 5 | 6 | + |\n\|___|___|___|___|\n\| 7 | 8 | 9 | - |\n\|___|___|___|___|\n\| 0 | * | \ |__|\n |___|___|___|__|\n");}
## Output of the program
 _______________\
 | 1 | 2 | 3 |  |\
 |___|___|___|  |\
 | 4 | 5 | 6 | +|\
 |___|___|___|__|\
 | 7 | 8 | 9 | -|\
 |___|___|___|__|\
 | 0 | * | \ |  |\
 |___|___|___|__|
# 18. Program of Addition of 2x2 Matrix
#include<stdio.h>\
int main()\
{float a,b,c,d,e,f,g,h,i,j,k,l;\
printf("\nSample of Ist matrix: | a=1b=2 |\nSample of 2nd matrix: | e=5f=6 |\n| f=7| c=3d=4 |\n\n\h=8 |\n\n");
printf("Enter The Valve of a: ");\
scanf("%f",&a);\
printf("Enter The Valve of b: ");\
scanf("%f",&b);\
printf("Enter The Valve of c: ");\
scanf("%f",&c);\
printf("Enter The Valve of d: ");\
scanf("%f",&d);\
printf("Enter The Valve of e: ");\
scanf("%f",&e);\
printf("Enter The Valve of f: ");\
scanf("%f",&f);\
printf("Enter The Valve of g: ");\
scanf("%f",&g);\
printf("Enter The Valve of h: ");\
scanf("%f",&h);\
i = a+e;\
j = b+f;\
k = c+g;\
l = d+h;\
printf("\n\nSum of Matrix(A+B) is: | %.2f  %.2f |\n
i = a-e;\
j = b-f;\
k = c-g;\
l = d-h;\
printf("\n\nSubstraction of Matrix(A-B) is: | %.2f  %.2f |\n| %.2f  %.2f |",i,j,k,l);\
i = e-a;\
j = f-b;\
k = g-c;\
l = h-d;\
printf("\n\nSubstraction of Matrix(B-A) is: | %.2f%.2f |\n| %.2f  %.2f |",i,j,k,l);\
return 0;}
## Output of the program
Sample of Ist matrix: | a=1| c=3d=4 |
b=2 |\
Sample of 2nd matrix: | e=5| f=7h=8 |
f=6 |\
Enter The Valve of a: 7\
Enter The Valve of b: 5\
Enter The Valve of c: 4\
Enter The Valve of d: 0\
Enter The Valve of e: 3\
Enter The Valve of f: 5\
Enter The Valve of g: 9\
Enter The Valve of h: 1\
Sum of Matrix(A+B) is: \
| 10.00 13.00 |\
| 1.00  10.00 |\
Substraction of Matrix(A-B) is: \
|  4.00  0.00 |\
| -5.00 -1.00 |
Substraction of Matrix(B-A) is: 
| -4.00 0.00 |\
|  5.00 1.00 |
# 19. Program of Multiplication of 2 Matrices
#include <stdio.h>\
int main()\
{ int m, n, p, q, c, d, k, sum = 0;\
  int first[10][10], second[10][10], multiply[10][10];\
 
  printf("Enter the number of rows and columns of first matrix\n");\
  scanf("%d%d", &m, &n);\
  printf("Enter the elements of first matrix\n");\
  for (  c = 0 ; c < m ; c++ )\
  for ( d = 0 ; d < n ; d++ )\
  scanf("%d", &first[c][d]);\
 
  printf("Enter the number of rows and columns of second matrix\n");\
  scanf("%d%d", &p, &q);\
 
  if ( n != p )\
  printf("Matrices with entered orders can't be multiplied with each other.\n");\
  else\
 {printf("Enter the elements of second matrix\n");\
 for ( c = 0 ; c < p ; c++ )\
 for ( d = 0 ; d < q ; d++ )\
 scanf("%d", &second[c][d]);\
 for ( c = 0 ; c < m ; c++ )\
{for ( d = 0 ; d < q ; d++ )\
{for ( k = 0 ; k < p ; k++ )\
{sum = sum + first[c][k]*second[k][d];}\
multiply[c][d] = sum;\
sum = 0;}\
 }\
 
 printf("Product of entered matrices:-\n");\
 for ( c = 0 ; c < m ; c++ )\
{for ( d = 0 ; d < q ; d++ )\
 printf("%d\t", multiply[c][d]);\
 printf("\n");}\
}\
 return 0;}\
##Output of the program
Enter the number of rows and columns of first matrix: 3 3\
Enter the elements of first matrix\
1 2 0\
0 1 1 \
2 0 1 \
Enter the number of rows and columns of second matrix: 3 3\
Enter the elements of second matrix\
1 1 2\
2 1 1 \
1 2 1\
Product of entered matrices:-\
5	3	4	\
3	3	2	\
3	4	5\
# 20. Program of FizzBuzz in a continues loop
#include<stdio.h>\
int main()\
{int n,x;\
printf("\nEnter The Integer: ");\
scanf("%d",&n);\
printf("\n");\
{for(x=1;x<=n;x++)\
if(x%15==0)\
printf("FizzBuzz\n");\
else if(x%3==0)\
printf("Fizz\n");\
else if(x%5==0)\
printf("Buzz\n");\
else\
printf("%d\n",x);}\
return 0;}
## Output of the program
Enter The Integer: 17\
1\
2\
Fizz\
4\
Buzz\
Fizz\
7\
8\
Fizz\
Buzz\
11\
Fizz\
13\
14\
FizzBuzz\
16\
17
