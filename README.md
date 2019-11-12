# PPS
## My Details
**Name** - divya chaudhary
**CRN** -1915310
**Branch** - CSE


## 1) To print name using puts.
```c

/* Program to print your name */

#include<stdio.h>
int main()
{       
puts("******************");
puts("Divya Chaudhary");
puts("******************");
return 0;
}


```
![](https://i.imgur.com/VsQniRp.png)

## 2) To print College address
```c
/* College Address */
 
#include<stdio.h>
int main()
{
printf("\n\t\tGuru Nanak Dev Engineering College");
printf("\n\t\t\tGill Road,");
printf("\n\t\t\tLudhiana,Punjab");
return 0;
}

```
![](https://i.imgur.com/kg4fMIp.png)
## 3) Program to add two integers .

```c
/* To add two integers */

#include<stdio.h>
int main()
{
int a,b,c;                                                               
printf("enter first number");
scanf("%d",&a);
printf("enter second number");
scanf("%d",&b);
c=a+b;
printf("sum of numbers is %d",c);
return 0;
}

```
![](https://i.imgur.com/cxUSpVu.png)
## 4) Program to find quotient and remainder.
```c
/* To find quotient and remainder */
#include<stdio.h>
int main()
{
int a,b,c,d;
printf("\n enter divident");
scanf("%d",&a);
printf("\n enter the divisor");
scanf("%d",&b);
c=a%b;
d=a/b;                                                   
printf(" \n remainder is %d",c);
printf(" \nquotient is %d",d);
return 0;
}

```
![](https://i.imgur.com/rrpSzRI.png)
## 5) Program to swap two variables without 3rd variable.
```c

/* Swapping without 3rd variable  */

#include<stdio.h>
int main()
{
int a,b;
printf("enter value of A:");
scanf("%d",&a);
printf("enter value of B:");
scanf("%d",&b);
a=a+b;
b=a-b;                                                   
a=a-b;
printf("\n value of A:%d ",a);
printf("\n value of B:%d",b);
return 0;
}                                                       
```
![](https://i.imgur.com/Enhp5Ee.png)
## 6) Program to check even odd number.
```c
/* To find whether number is even or odd */

#include<stdio.h>
int main()
{
int num,temp;
printf("enter the number");
scanf("%d", &num);

if(num%2==0)
{
printf("\n number is even");                             
}
else
{
printf("\n number is odd");
}
return 0;
}  

```
![](https://i.imgur.com/Nh10ypY.png)
## 7) Finding greteast of two numbers.

```c
/* Largest one in two */
#include<stdio.h>
int main()
{  
int a,b;
printf("enter two numbers A and B");
scanf("%d%d",&a,&b);
if(a>b)
{
printf("\n  A is largest");
}
else
{
printf("\n B is largest");
}
return 0;
}                                                        
```
![](https://i.imgur.com/E78ZgW6.png)

## 8) Find greatest of three number .

```c
/* Largest of three number */

#include<stdio.h>
int main()
{
int a,b,c;
printf("enter the numbers");
scanf("%d%d%d",&a,&b,&c);
if(a>b &&  a>c)
  { 
printf("a is greatest = %d\n ",a);
   }
else if(b>c  && b>a)
 {
printf(" b is greatest = %d",b);
 }
else  
{
printf(" c is greatest= %d",c);
}
return 0;
} 
```           
![](https://i.imgur.com/k24cwTX.png)

## 9) Program to assign grade to student according to percentage.
```c

/* To find grade of a student by marks */

#include<stdio.h>
int main()
{
int pps ,chm, eng,mat, agg;
float perc;
printf(" enter marks in pps, chm, eng and mat: \n");
scanf("%d%d%d%d", &pps,&chm,&eng,&mat);
agg= pps+chm+eng+mat;
perc=agg/400.0*100;
if (perc>=90)
{
printf("\n Grade A");
}
else if (perc>=80 && perc<90)
{
printf("Grade B");
}
else if ( perc>=70 && perc<80)
{
 printf(" Grade C");
}
 else if( perc>=60 && perc<70)                           
{                                                        
printf(" Grade D");
}
else if(perc>=50 && perc<60)
{ 
printf("Grade E");
}
else                                              
{
printf("FAIL");
}
return 0;
}
```
![](https://i.imgur.com/ZTaubbP.png)
## 10) Program to print roots of quadratic equation.
```c
/*Program to print roots */

  #include<stdio.h>

  #include<math.h>
  
int main()

{
   
 double a, b, c, discriminant, root1, root2, realPart, imaginaryPart;
 
 printf("Enter coefficients a, b and c: ");
   
 scanf("%lf %lf %lf",&a, &b, &c);
  
 discriminant = b*b-4*a*c;
  
 if (discriminant > 0)
    
{
  
   root1 = (-b+sqrt(discriminant))/(2*a);
 
   root2 = (-b-sqrt(discriminant))/(2*a);
     
   printf("root1 = %.2lf and root2 = %.2lf",root1 , root2);
   
      }
   
 else if (discriminant == 0)
    
{
 
       root1 = root2 = -b/(2*a);
       
       printf("root1 = root2 = %.2lf;", root1);
   
 }
    
else
   
 {
      
  realPart = -b/(2*a);
       
 imaginaryPart = sqrt(-discriminant)/(2*a);
      
  printf("root1 = %.2lf+%.2lfi and root2 = %.2f-%.2fi", realPart, imaginaryPart, realPart, imaginaryPart);
   
 }
 
  return 0;
}

```
![](https://i.imgur.com/om9pG8J.png)
## 11) Program to check year is leap or not.

```c
/* To find whether year is leap or not */

#include <stdio.h>
int main()
 { 
int year;
 printf("Enter a year: "); 
    scanf("%d",&year);
 if(year%4 == 0) 
{
        if( year%100 == 0) {
            // year is divisible by 400, hence the year is a leap// year
            if ( year%400 == 0)
     printf("%d is a leap year.",year);
            else printf("%d is not a leap year.", year);
        }
        else printf("%d is a leap year.", year );
    }
    else printf("%d is not a leap year.", year);
    
    return 0;
}
                                                                                    
```
![](https://i.imgur.com/K0mOXOG.png)

## 12) Program to print table of 5.
```c
/* Table of 5 */

#include<stdio.h>
 int main() 
 { int res,i;
 for(int i=1;i<=10;i++)
 {  
res=5*i;
                                                                          
   printf("\n5*%d=%d",i,res);
   }                                                                      
   return 0;
}

```
![](https://i.imgur.com/sa2DvaK.png)
## 13) To make simple calculator using switch case.
```c

/* C Program to Create Simple Calculator using Switch Case */
 
#include<stdio.h>
int main()
 { char operator;
 double firstNumber,secondNumber; 
    printf("Enter an operator (+, -, *,): ");
 scanf("%c", &operator);
 printf("Enter two operands: ");
 scanf("%lf%lf",&firstNumber, &secondNumber);
 switch(operator)
 {                                                     
        case '+': 
printf("%.1lf + %.1lf = %.1lf",firstNumber,secondNumber, firstNumber + secondNumber);
 break;
        case '-': printf("%.1lf - %.1lf = %.1lf",firstNumber,  secondNumber, firstNumber - secondNumber);
 break;
        case '*': printf("%.1lf * %.1lf = %.1lf",firstNumber,  secondNumber, firstNumber * secondNumber);
 break;                                                  
        case '/': printf("%.1lf / %.1lf = %.1lf",firstNumber, secondNumber, firstNumber / secondNumber); 
break;
       
        default: printf("Error! operator is not correct");
    }
    
    return 0;                                            
}	
```
![](https://i.imgur.com/D4YN5q3.png)
## 14) To calculate reverse of a number.

```c
/* To find reverse of a Number*/

 #include<stdio.h>
 int main()
 {
 int n,reverse=0;
 printf("enter a  number to reverse\n");
 scanf("%d",&n);
 while(n!=0)
  {
 reverse = reverse*10; reverse= reverse+n%10; n=n/10;
  }
   printf("reverse of entered number is =%d\n",reverse);
 return 0;
  }

```
![](https://i.imgur.com/OGpH2Jm.png)
## 15) To check whether number is palindrome or not.
```c

/* Palindrome */

#include <stdio.h>
int main()
 {
 int n, reversedInteger = 0, remainder,originalInteger;
 printf("Enter an integer: ");
 scanf("%d", &n); 
originalInteger = n;
while( n!=0 )
 {
 remainder = n%10;
 reversedInteger =reversedInteger*10 + remainder;
 n /= 10;
}
if (originalInteger == reversedInteger)
 printf("%d is a palindrome.", originalInteger);

 else                                                    
 printf("%d is not a palindrome.", originalInteger);
 return 0;
}				

```
![](https://i.imgur.com/JzWL6Nj.png)
### 16) To check whether a number is prime or not.

```c
/* Program to check prime no. */

#include<stdio.h>
int main()
 { int n, i, flag = 0;
 printf("Enter a positive integer:");
 scanf("%d", &n);
 for(i = 2; i <= n/2; ++i)
{
  if(n%i == 0)
 { flag = 1; break;
        }
    }
if(n==1)
{
printf(" 1 is neither prime nor composite");
}                                                        
else
{
if(flag==0)
printf("%d is a prime no. ",n);
else
printf("%d is not a prime no.",n);
}                                                        
return 0;
}
```
![](https://i.imgur.com/MJ3w6MY.png)
### 17) Program to print prime number to 100.
```c
/* Prime number from 1 to 100 */
 
#include<stdio.h>
int main()
 {      
 int i,j;
 for(i=2;i<100;i++)
 {
 for(j=2;j<i;j++)
 { 
if(i%j==0)
 break;
 else
{
 if(i==j+1)
 printf("%d \n",i);
}
}       
}       
}
   
   ```
   ![](https://i.imgur.com/ApVQ4jy.png)
   
## 18) Program to check whether a number is armstrong or not.
```c
/* To check armstrong number */

#include <stdio.h>
int main()
 {
 int number, originalNumber, remainder, result = 0;
 printf("Enter a three digit integer: "); 
    scanf("%d", &number);
 originalNumber = number;
 while(originalNumber != 0)
 {
        remainder = originalNumber%10;
 result += remainder*remainder*remainder; originalNumber /=10;
    }

    if(result == number)
 printf("%d is an Armstrong number.",number);
    else
 printf("%d is not an Armstrong number.",number); 
    return 0;
}

```
![](https://i.imgur.com/LiGT6CK.png)
## 19) Print Different Patterns.
```c
#### i) 

/* Pattern 1*/

#include <stdio.h>
int main() {
    
   int i,j,r;
    
   printf("Enter number of rows: ");
    scanf("%d",&r);
    
for(i=1; i<=r; ++i)
    {
        for(j=1; j<=i; ++j)
        {
            printf("%d ",j);
        }
        printf("\n");
    }
    return 0;
}


```
![](https://i.imgur.com/rHl5Jw5.png)
#### ii) 
```c
  /* Pattern 2*/
  
#include <stdio.h>
int main() {
    
   int r,i,j,num= 1;
   printf("Enter number of rows: ");
    scanf("%d",&r);
    for(i=1;i<=r;i++)
    {
        for(j=1;j<=i;++j)
        {
            printf("%d",num);
            ++num;
        }
        printf("\n");
    }
    return 0;
}

 
 ```
 ![](https://i.imgur.com/utuIG1a.png)
### 20)  Program to find largest from 1 dimensional array.
```c 
 
 /* Largest in 1 dimensional array */

#include <stdio.h>
int main()
 {
 int i, n;
 float arr[100];
 printf("Enter total number of elements(1 to 100): ");
 scanf("%d", &n);
 printf("\n");
    for(i = 0; i < n; ++i)                               
 {
 printf("Enter Number %d: ", i+1); 
       scanf("%f", &arr[i]);
    }
    for(i = 1;i<n;++i)
{
       if(arr[0] < arr[i])                               
       arr[0] = arr[i];                                  
    }
    printf("Largest element = %.2f",
 arr[0]);
 return 0;
}
```
![](https://i.imgur.com/B0uiWCC.png)

### 21) To find sumof the N natural numbers in an array.
```c
/* Sum of N no.s in array */
     
#include<stdio.h>
int main()
 {     
 int n, sum = 0, c, array[100];
 printf("Enter  the number of integers you want to add: ");
 scanf("%d", &n); 
  printf("\n\nEnter %d integers \n\n", n);
 for(c = 0; c < n; c++)
 {  
    scanf("%d", &array[c]); sum += array[c]; 
    }
    printf("\n\nSum = %d\n\n", sum);
 return 0;
}
     
 ```    
 ![](https://i.imgur.com/Q3fEQhx.png)
### 22) Program to add two matrices .
```c
/*  Addition of matrix */

#include <stdio.h>
 int main()
{ 
 int r, c, a[100][100], b[100][100], sum[100][100], i,j;
 printf("Enter number of rows (between 1 and 100): "); 
    scanf("%d", &r);
 printf("Enter number of columns (between 1 and 100): ");
 scanf("%d", &c);                                                           
 printf("\nEnter elements of 1st matrix:\n");
 for(i=0; i<r; ++i)
 for(j=0; j<c; ++j)
 {
 printf("Enter element a%d%d:",i+1,j+1);
 scanf("%d",&a[i][j]);
        }                                                
    printf("Enter elements of 2nd matrix:\n");
 for(i=0; i<r; ++i)
 for(j=0; j<c; ++j)
 {
  printf("Enter element a%d%d: ",i+1, j+1);
 scanf("%d",&b[i][j]);
        }
 for(i=0;i<r;++i)
 for(j=0;j<c;++j)                                        
 {
 sum[i][j]=a[i][j]+b[i][j];
        }
 printf("\nSum of two matrices: \n");
 for(i=0;i<r;++i)
{  
            printf("%d ",sum[i][j]); if(j==c-1) { printf("\n\n");
            }
        }
    return 0;
}
         for(j=0;j<c;++j)    
   

```
![](https://i.imgur.com/1ACh16M.png)
## 23) Program to multiply two matrices 
```c
#include <stdio.h>
int main()
 {
 int m, n, p, q, c, d, k, sum = 0;
 int first[10][10], second[10][10], multiply[10][10];
  printf("Enter number of rows and columns of first matrix\n");
  scanf("%d%d", &m, &n);
 printf("Enter elements of first matrix\n");
  for (c = 0; c < m; c++)
 for (d = 0; d < n; d++)
 scanf("%d",&first[c][d]);
  printf("Enter number of rows and columns of second matrix\n");
 scanf("%d%d", &p, &q);
  if (n != p)
 printf("The matrices can't be multiplied with each other.\n");
  else { printf("Enter elements of second matrix\n");
    for (c = 0; c < p; c++)
 for (d = 0; d < q; d++)
 scanf("%d", &second[c][d]);
  for (c = 0; c < m; c++)
 {
 for (d = 0; d < q; d++)
 {    
 for (k = 0; k < p; k++)
 {
          sum = sum + first[c][k]*second[k][d];
        }
        multiply[c][d] = sum;
 sum = 0;
      } }
    
    printf("Product of the matrices:\n");
    for (c = 0; c < m; c++)
 {
 for (d = 0; d < q; d++)
  printf("%d\t", multiply[c][d]);
      printf("\n");
    }
  }
  return 0;
}       

```
![](https://i.imgur.com/ZybB8eA.png)

## 24) Program to check whether  a string is palindrome or not .

```c
 
#include <stdio.h>
#include <string.h>
int main()
{ char string1[20];
 int i, length;
 int flag = 0;
    
    printf("Enter a string:");
 scanf("%s", string1);
    
    length = strlen(string1);
    
    for(i=0;i < length ;i++)
{
 if(string1[i] != string1[length-i-1])
{     
            flag = 1;
 break;
   }
}       
        
    if (flag)
 {    
 printf("%s is not a palindrome", string1);           
    }    
    else
 {
 printf("%s is a palindrome", string1);
    }
    return 0;

```
![](https://i.imgur.com/PhfDgH2.png)
## 25) Program to perform basic operations like lenghth of string ,string concat, string copy ,string compare and string reverse.

```c
///fundamental string operation, lenth, concatenation, compare and copy strings without string.h


#include <stdio.h> 
#include <stdlib.h>
  
int find_length(char string[])
{
    int len = 0, i;
    for (i = 0; string[i] != '\0'; i++) {
      len++;
    }
    return len;
  }

void join_strings(char string1[], char string2[]) {
  int i, len1, len2;
  len1 = find_length(string1);
  len2 = find_length(string2);
  for (i = len1; i < len1 + len2; i++) {
    string1[i] = string2[i - len1];
  }
  string1[i] = '\0'; //adding null character at the end of input
}
/*returns 0 if thery are same otherwise returns 1*/

int compare_strings(char string1[], char string2[]) {
  int len1, len2, i, count = 0;
  len1 = find_length(string1);
  len2 = find_length(string2);
   if (len1 != len2)
    return 1;
  for (i = 0; i < len1; i++) {
    if (string1[i] == string2[i])
      count++;
  }
  if (count == len1)
    return 0;
  return 1;
}

void copy_string(char destination[], char source[]) {
  int len, i;
  len = find_length(source);
  for (i = 0; i < len; i++) {
    destination[i] = source[i];
  }
  destination[i] = '\0';
}

int main() {
  char string1[20], string2[20]; //string variables declaration with size 20
  int choice;
  while (1) {
    printf("\n1. Find Length \n2. Concatenate \n3. Compare \n4. Copy \n5. Exit\n");
    printf("Enter your choice: ");
    scanf("%d", & choice);
    switch (choice) {
    case 1:
      printf("Enter the string: ");
      scanf("%s", string1);
      printf("The length of string is %d", find_length(string1));
      break;
    case 2:
      printf("Enter two strings: ");
      scanf("%s%s", string1, string2);
      join_strings(string1, string2);
      printf("The concatenated string is %s", string1);
      break;
    case 3:
      printf("Enter two strings: ");
      scanf("%s%s", string1, string2);
      if (compare_strings(string1, string2) == 0) {
        printf("They are equal");
      } else {
        printf("They are not equal");
      }
      break;
    case 4:
      printf("Enter a string: ");
      scanf("%s", string1);
      printf("String1 = %s\n");
      printf("After copying string1 to string 2\n");
      copy_string(string2, string1);
      printf("String2 = %s", string2);
      break;
    case 5:
      exit(0);
    }
  }
  return 0;
}
```
![](https://i.imgur.com/aBtDvuO.png)
## 26) Programs to swap two numbers using call by value and call by refernce.
```c
#### call by refernce:-

#include <stdio.h>
 void swap(int num1, int num2)
 { int temp;
 printf("In Function values before swapping: %d %d\n", num1, num2);
 temp = num1;
 num1 = num2;
 num2 = temp;
 printf("In Function values after swapping: %d %d\n\n", num1, num2);
}
 int main() { int n1, n2;
 printf("Enter two numbers: "); 
    scanf("%d%d", &n1, &n2); 
 printf("In Main values before swapping: %d%d\n\n", n1, n2); 
    swap(n1, n2);
 printf("In Main values after swapping: %d %d",n1, n2);
 return 0;
}  
```
![](https://i.imgur.com/T5T2Iux.png)
#### call by value:- 
```c   
#include <stdio.h>
 void swap(int num1, int num2)
 {
 int temp;
 printf("In Function values before swapping: %d %d\n", num1, num2);
 temp = num1;
 num1 = num2; 
 num2 = temp;
 printf("In Function values after swapping: %d %d\n\n", num1, num2);
}
 int main()
 { int n1, n2;
 printf("Enter two numbers: "); 
    scanf("%d%d", &n1, &n2); 
 printf("In Main values before swapping: %d%d\n\n", n1, n2); 
    swap(n1, n2);
 printf("In Main values after swapping: %d %d", n1, n2); 
 return 0;
}
  
    
  ```  
  ![](https://i.imgur.com/yHURmPd.png)  
## 27) Program to calculate factorial of a number with and without recursion both.

```c
#### with Recursion:-


#include<stdio.h>
 
long factorial(int);
 
int main() { int n; long f;
 
  printf("Enter an integer to find its factorial\n");
 scanf("%d", &n);
    
  if (n < 0)
 printf("Factorial of negative integers isn't defined.\n");
  else
 {
 f = factorial(n);
 printf("%d! = %ld\n", n, f);
  }
  return 0;                                              
}

long factorial(int n)
 {
 if (n == 0)
 return 1;
 else 
return(n *factorial(n-1));
}

```
![](https://i.imgur.com/6lKwZn4.png)
#### without recursion:-
```c
#include <stdio.h>
#include <stdlib.h>
int main()
 {
 int n, i;
 unsigned long long factorial = 1;
 printf("Enter a number to find factorial: ");
 scanf("%d",&n);
    if (n < 0)
 printf("Error! Please enter any positive integer number");
   else
 {
 for(i=1; i<=n; ++i)
 { factorial *= i; 
        }
        printf("Factorial of Number %d = %llu", n, factorial);
    }
 
    return 0;
}

```
![](https://i.imgur.com/rziA6TD.png)

## 28) Program to print fibonacci series with and without recursion both.
```c
#### Without recursion:-

/* Program to print fibonaci series */

#include <stdio.h>
 int main()
 {  
 int x, y, z, n, i; x=0; y=1;
 printf(" Enter value of n: ");
 scanf("%d", &n);
 printf(" Fibonacci Series: ");
 printf(" %d", x);
 printf(" %d", y);
 for( i=0; i<n-2; i++)                                   
         {
                  z = x+y;
 printf(" %d", z);
 x = y;
 y = z;
         }
return 0;                                                
}
```
![](https://i.imgur.com/iHOC204.png)
#### with recursion:-
```c
/* program to print fibonaci series */


#include <stdio.h>
int fibo(int);    
int main()
 {
 int num;
 int result;
 printf("Enter the nth number in fibonacci series: ");
 scanf("%d", &num);
 if (num < 0)
 {
        printf("Fibonacci of negative number is not possible.\n");
    }
    else
 {                                                                          
 result = fibo(num);
 printf("The %d number in fibonacci series is %d\n", num, result);
    }
    return 0;
}
int fibo(int num)
 {                                                       
 if (num == 0)
 {
 return 0;
    }
    else if (num == 1)
 {
 return 1;
    }
    else
 {
 return(fibo(num - 1) + fibo(num - 2));
    }
}

```     
![](https://i.imgur.com/wuH9QwF.png)
## 29) Program to calculate average of 5 numbers using function.
```c

 /* program to find average of 5 numbers using functions */

#include<stdio.h>
void main()
 {  
 int a,b,c,d,e,sum,avg;
 printf("enter the five  values");
 scanf("%d%d%d%d%d",&a,&b,&c,&d,&e);
 sum=a+b+c+d+e;
 avg= sum/5;
 printf("average=%d",avg);
 }
 
 ```
 ![](https://i.imgur.com/k8REu5Z.png)
## 30) Program to implement linear serach and binary.
```c

/* Program to implement linear search */


#include <stdio.h>
int main()
 { int array[100], search, c, n;
  printf("Enter number of elements in array\n");
 scanf("%d", &n);
  printf("Enter %d integer(s)\n", n);
  for (c = 0; c < n; c++)
 scanf("%d", &array[c]);
  printf("Enter a number to search\n");
 scanf("%d", &search);
  for (c = 0; c < n; c++)
 {  
 if (array[c] == search)
 {
      printf("%d is present at location %d.\n", search, c+1);
      break;
    }                                                
  }
  if (c == n)
 printf("%d isn't present in the array.\n", search);

  return 0;
}



```
![](https://i.imgur.com/i67ujXT.png)
  /* program to implement binary search*/
```c
#include <stdio.h>
 
int main()
 { int c, first, last, middle, n, search, array[100];
   printf("Enter number of elements\n");
 scanf("%d",&n);
 printf("Enter %d integers\n", n);
 for (c = 0; c < n; c++)
 scanf("%d",&array[c]);
 printf("Enter value to find\n");
 scanf("%d", &search);
 first = 0; last = n - 1; middle = (first+last)/2;
 while (first <= last)
 {    
 if (array[middle] < search)
 first = middle + 1;
      else if (array[middle] == search)
 {
 printf("%d found at  location %d.\n", search, middle+1);
 break;
      }
      else
 last = middle - 1;
  middle = (first + last)/2;
   }
   if (first > last)
 printf("Not found! %d isn't present in the list.\n", search);
   return 0;
}

```
![](https://i.imgur.com/r11UsDN.png)


## 31) Program to implement bubble sort.

```c
   /* Bubble sort implementation */


#include <stdio.h>
int main()
 {
 int array[100], n, c, d, swap;
  printf("Enter number of elements\n");
 scanf("%d", &n);
  printf("Enter %d integers\n", n);
  for (c = 0; c < n; c++)
 scanf("%d", &array[c]);
 for (c = 0 ; c < n - 1; c++)
 {
 for (d = 0 ; d < n - c - 1; d++)
    { 
      if (array[d] > array[d+1])
      {
        swap = array[d];
 array[d] = array[d+1];
 array[d+1] = swap;
      }
    }
  }
  printf("Sorted list in ascending order:\n");           
                                                         
  for (c = 0; c < n; c++) printf("%d\n", array[c]);                         

  return 0;
}

```
![](https://i.imgur.com/AtBu8CZ.png)
## 32) Program to store information of 10 students using array of structures.

```c

#include<stdio.h>
struct student
{
  char name[20],address[30];
  int grade,roll,dob;
};

int main()
{
  struct student s[10];
  int i;
  for(i=0;i<10;i++)
  {
    printf("\nEnter records for student[%d]\n",i+1);
    printf("Enter name: ");
    gets(s[i].name);
    printf("Enter address: ");
    gets(s[i].address);
    printf("Enter class, roll number and date of birth(year): ");
    scanf("%d%d%d",&s[i].grade,&s[i].roll,&s[i].dob);
  }
  printf("Records of the 10 students are here");
  for(i=0;i<10;i++)
  {
    printf("\nStudent %d",i+1);
    printf("\nName: %s",s[i].name);
    printf("\nAddress: %s",s[i].address);
    printf("\nClass: %d",s[i].grade);
    printf("\nRoll No.: %d",s[i].roll);
    printf("\nDOB: %d",s[i].dob);
    printf("\n");
  }
  return 0;
}

```
![](https://i.imgur.com/zbbin1a.png)
## 33) Programs to compute the transpose of a matrix.
```c

#include <stdio.h>
int main()
 {
 int m, n, c, d, matrix[10][10], transpose[10][10];
   printf("Enter the number of rows and columns of matrix\n"); 
   scanf("%d%d", &m, &n);
   printf("Enter elements of the matrix\n");
   for (c = 0; c < m; c++)
 for(d = 0; d < n; d++)
 scanf("%d", &matrix[c][d]);
   for (c = 0; c < m; c++)
 for( d = 0 ; d < n ; d++ )
         transpose[d][c] = matrix[c][d];
   printf("Transpose of the matrix:\n");
   for (c = 0; c < n; c++)
 {
 for (d = 0; d < m; d++)
         printf("%d\t", transpose[c][d]);
      printf("\n");
   }
  
   return 0;                                             
} 

```
![](https://i.imgur.com/btNJfmc.png)
## 34) Program to print the address of variable using pointer.
```c
   
#include <stdio.h>
int main(void)
 {
        int a; float b; char c;
        int *ptr_a = &a;
        float *ptr_b = &b;
        char *ptr_c = &c;
        printf("Address of a: %p\n", ptr_a);
 printf("Address of b:%p\n", ptr_b);
 printf("Address of c: %p\n", ptr_c);
 return 0;
} 
```
![](https://i.imgur.com/tTWdeyX.png)
## 35) Program to access array using pointer.
```c
#include<stdio.h>
int main()
 {
 int data[5], i;
 printf("Enter elements: ");
 for(i =0; i < 5; ++i)
 scanf("%d", data + i);
 printf("You entered: \n");
 for(i = 0; i < 5; ++i)
 printf("%d\n", *(data + i));
 return 0;
}
```

![](https://i.imgur.com/jJWlgAc.png)

