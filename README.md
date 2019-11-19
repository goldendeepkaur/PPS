# PPS
Programming for Problem Solving
![](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcT62gxSPP7isA7BEncc_4ZyUxYKsVKbV8ruG3_L9Chk3yKHEZ9y)
# **Programming for Problem Solving**
## **Name** - Naman Marria
## **CRN -1915369**
## **Branch - CSE-C2**
## **Submitted to:- Ms Goldendeep Kaur **
---

### 1) To print name.
```C
      /* Program to print your name */

#include<stdio.h>
int main() {

puts("***************");
puts("Naman Marria");
puts("***************");

return 0;
}

```
<img src="https://i.imgur.com/ypHqS9z.jpg">

### 2) To print College address.
```C
        /* College Address */
 
#include<stdio.h>
int main() {

printf("\n\t\t\tGuru Nanak Dev Engineering College,");
printf("\n\t\t\tGill Road,");
printf("\n\t\t\tLudhiana, Punjab\n");

return 0;
}
<img src ="">
```
<img src="https://i.imgur.com/bhEApPD.jpg">

### 3) Program to add two integers.
```C
     /* To add two integers */

#include <stdio.h>
int main() {
    
int a,b;

printf("\nEnter the numbers....");

printf("\nA:");
scanf("%d",&a);

printf("\nB:");
scanf("%d",&b);

a=a+b;

printf("\n Sum of the number is %d ",a);

return 0;

}
```
<img src="https://i.imgur.com/4DdtQBP.jpg">

### 4) Program to find quotient and remainder.
```C
    /* To find quotient and remainder */

#include <stdio.h>

int main() {
    
int a,b,r,q;

printf("\nEnter the Dividend:");
scanf("%d",&a);

printf("\nEnter the divisor:");
scanf("%d",&b);

r=a%b;
q=a/b;

printf("\nRemainder: %d",r);
printf("\nQuotient: %d",q);

return 0;
}

```
<img src="https://i.imgur.com/0W6jXQU.png">


### 5) Program to swap two variables without 3rd variable.
```C
    /* Swapping without 3rd variable  */

#include <stdio.h>
int main() {
    
int a,b;

printf("\nEnter the value of A:");
scanf("%d",&a);

printf("\nEnter the value of B:");
scanf("%d",&b);

   a = a + b;
   b = a - b;
   a = a - b;
   
printf("\nA: %d",a);
printf("\nB: %d",b);

return 0;
}

```
<img src="https://i.imgur.com/k8DDgWr.png">

### 6) Program to check even odd number.
```C
/* To find whether number is even or odd */

#include<stdio.h>                                                            int main()
{
        int x;
        printf("enter an integer \n");                                       
        scanf("%d",&x);
        if(x%2==0)                                                           
        printf("even\n");
        else                                                                 
        printf("odd\n");

        return 0;
}

```
<img src="https://i.imgur.com/cZ6XARD.png">

### 7) Finding greteast of two numbers.
```C
     /* Largest one in two */

#include<stdio.h>
int main()
{
        int a,b;
                printf("enter the two integers a and b respectively \n");
                scanf("%d%d",&a,&b);

        if(a==b)
                printf("Both  the numbers are equal\n");
        else
                {
                        if(a>b)
                        printf("a is greater than b\n",a);
                        else
                        printf("b is greater than a\n",b);
                }
return 0;
}

```
<img src="https://i.imgur.com/jp4XnM9.png">

### 8) Find greatest of three number .
```C
/* Largest of three number */

#include<stdio.h>
int main()
{
        int x,y,z;
        printf("enter the 3 integers -a,b,c respectively \n");
        scanf("%d%d%d",&x,&y,&z);
        if(x>y && x>z)
        printf("a is the greatest number \n",x);
        else
                {                                                            
                        if(y>x && y>z)
                        printf("b is the greatest number \n",y);             
                        else
                        printf("c is the greatest number \n",z);             
                }
return 0;                                                                    
               

```
<img src="https://i.imgur.com/AZ9vB3V.png">

### 9) Program to assign grade to student according to percentage.
```C
/* To find grade of a student by marks */

#include<stdio.h>
int main() { 
    
  int s1,s2,s3,s4,s5,agg;
  float perc;

  printf("Enter the Marks in 5 Subjects Respectively:\n");

scanf("%d%d%d%d%d",&s1,&s2,&s3,&s4,&s5);

agg=s1+s2+s3+s4+s5; // Aggregate Marks
  
  perc=agg/500.0*100;  // Perc Marks

  if(perc>=90)
  {
      printf("\nA");
      
  }
  
  else if (perc>=80 && perc<90)
  { 
      printf("\nB");
      
  }
  
  else if(perc>=70 && perc<80)
  {
      printf("\nC");
      
  }
  
  else if(perc>=60 && perc<70)
  { 
      printf("\nD");
  }
  else if(perc>=50 && perc<60)
  {
      printf("\nE");
  }
  else 
     {
          printf("\nScope of Improvement....");
    } 
    return 0;
}
```
<img src="https://i.imgur.com/ssrLTTz.png">

### 10) Program to print roots of quadratic equation.
```C
/*Program to print roots */

#include <stdio.h>
#include <stdlib.h>
#include <math.h>
 
int main() {
    float a, b, c, root1, root2;
    float realp, imagp, disc;
 
printf("Enter the values of a, b and c \n");
    scanf("%f %f %f", &a, &b, &c);
    
/* If a = 0, it is not a quadratic equation */

if (a == 0 || b == 0 || c == 0)
    {
        printf("Error: Roots cannot be determined \n");
        exit(1);
    }
    else
    {
        disc = b * b - 4.0 * a * c;
        if (disc < 0)
        {
            printf("Imaginary Roots\n");
            realp = -b / (2.0 * a) ;
            imagp = sqrt(abs(disc)) / (2.0 * a);
            printf("Root1 = %f  +i %f\n", realp, imagp);
            printf("Root2 = %f  -i %f\n", realp, imagp);
        }

else if (disc == 0)
        {
            printf("Roots are real and equal\n");
            root1 = -b / (2.0 * a);
            root2 = root1;
            printf("Root1 = %f\n", root1);
            printf("Root2 = %f\n", root2);
        }

else if (disc > 0 )
        {
            printf("Roots are real and distinct \n");
            root1 =(-b + sqrt(disc)) / (2.0 * a);
            root2 =(-b - sqrt(disc)) / (2.0 * a);
            printf("Root1 = %f  \n", root1);
            printf("Root2 = %f  \n", root2);
        }

}
   return 0;
}

```
<img src="https://i.imgur.com/dPqG2D0.png">

### 11) Program to check year is leap or not.
```C
/* To find whether year is leap or not */

#include<stdio.h>
int main()
{
        int year;
printf("enter a year :");
scanf("%d",&year);
        if(year%4==0)
        {       if(year%100==0)
                        {
                                if(year%400==0)
                                printf("%d is a leap year\n",year);

                                else
                                 printf("%d is not a leap year\n",year);

                        }
                else
                printf("%d is a leap year\n",year);

                 }
          else
                printf("%d is not a leap year .\n",year);

        return 0;       
}                       
                
```
<img src="https://i.imgur.com/HUAMcCB.png">

### 12) Program to print table of 5.
```C
/* Table of 5 */

#include<stdio.h>

int main() { int res;

for(int i=1;i<=10;i++) {

res=5*i;
    
   printf("\n5*%d=%d",i,res);
   }

   return 0;
}
```
<img src="https://i.imgur.com/tsPglL3.png">

### 13) To make simple calculator using switch case.
```C
/* C Program to Create Simple Calculator using Switch Case */
 
#include <stdio.h>
 
int main() {
	char Operator;
	float num1, num2, result = 0;
	
printf("\n Please Enter an Operator (+, -, *, /)  :  ");
scanf("%c", &Operator);
  	
printf("\n Please Enter the Values for two Operands: num1 and num2  :  ");
scanf("%f%f", &num1, &num2);
  	
switch(Operator)
  	{
  		case '+':
  			result = num1 + num2;
  			break;
  		case '-':
  			result = num1 - num2;
  			break;
  		case '*':
  			result = num1 * num2;
  			break;
  		case '/':
  			result = num1 / num2;
  			break;
		default:
			printf("\n You have enetered an Invalid Operator ");				    			
	}
  
printf("\n The result of %.2f %c %.2f  = %.2f \n", num1, Operator, num2, result);
	
return 0;
}

```
<img src="https://i.imgur.com/nh6QlRj.png">

### 14) To calculate reverse of a number.
```C
/* To find reverse of a Number*/

#include<stdio.h>
int main() { 

  int num,rev=0;

  printf("\nEnter the Number:");
  scanf("%ld",&num);

while(num!=0)
{ 
    rev = rev * 10;
    rev = rev + num%10;
    num = num/10;
  }
  

  printf("\nReversed number:%d",rev);

  printf("\n\n");
  return 0;
}


```
<img src="https://i.imgur.com/bcLhcLk.png">

### 15) To check whether number is palindrome or not.
```C
/* Palindrome */

#include<stdio.h>
int main()
{
        int n , reversedinteger =0,remainder,originalinteger;
        printf("enter an integer ");
        scanf("%d",&n);

        originalinteger=n;
        while(n!=0)
        {
                remainder=n%10;
                reversedinteger=reversedinteger*10+remainder;
                n/=10;
        }
        if(originalinteger==reversedinteger)
                        printf("%d is a palindrome.",originalinteger);
                else          
                        printf("%d is not a palindrome",originalinteger);
                
return 0;
}

```
<img src="https://i.imgur.com/5rQGP8B.png">

### 16) To check whether a number is prime or not.
```C
/* Program to check prime no. */

#include<stdio.h>
int main()
{
        int n,c=2;
                printf("enter a number to check whether it is prime\n");
                scanf("%d",&n);
        for(c=2;c<n;c++)
        {
                if(n%c==0)
                {
                printf("%d isn't prime.\n",n);
                break;
                }
        }
                if(c==n)
                printf("%d is prime.\n",n);
        return 0;
}

```
<img src="https://i.imgur.com/R1g79Wx.png">

### 17) Program to print prime number to 100.
```C
/* Prime number from 1 to 100 */
 
 #include<stdio.h>                                                            int main()
{                                                                                    for(int i=2;i<100;i++)
        {       for(int j=2;j<i;j++)
                {
                if(i%j==0)                                                                           break;
        else    
                if(i==j+1)
                printf("%d\n",i);
                }
        }
return 0;
}

 
 ``` 
<img src="https://i.imgur.com/YAdz3WX.png">

### 18) Program to check whether a number is armstrong or not.
```C
/* To check armstrong number */

#include <stdio.h>
int main()
{
    int number, originalNumber, remainder, result = 0;

printf("Enter a three digit integer: ");
    scanf("%d", &number);

originalNumber = number;

while (originalNumber != 0)
    {
        remainder = originalNumber%10;
        result += remainder*remainder*remainder;
        originalNumber /= 10;

}

if(result == number)
        printf("%d is an Armstrong number.",number);
    else
        printf("%d is not an Armstrong number.",number);

return 0;
}
 
```
<img src="https://i.imgur.com/V4nVoup.png">


### 19) Print Different Patterns.
i) Pattern 1.
```C
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
<img src="https://i.imgur.com/98sy3Bm.png">

### ii) Pattern 2. 
```C
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

<img src="https://i.imgur.com/1mKkswJ.png">

### 20) Program to find largest from 1 dimensional array.
```C 
/* Largest in 1 dimensional array */

#include<stdio.h>

int main()
{
        int array[100],maximum,size,c,location=1;
        printf("Enter the number of elements in array \n");
        scanf("%d",&size);

        printf("enter %d integers\n",size);

                for(c=0;c<size;c++)
                scanf("%d",&array[c]);
maximum=array[0];

for(c=1;c<size;c++)
        {
                if(array[c]>maximum)
                {
                        maximum=array[c];
                        location =c+1;
                }
        }

printf("Largest element is present at ;location %d and it's value is %d.\n",location,maximum);
return 0;
}

```
<img src="https://i.imgur.com/PtFRg8s.png">

### 21) To find sum of the N natural numbers in an array.
```C
/* Sum of N no.s in array */
     
#include<stdio.h>

int main() {
    
    int n, sum = 0, c, array[100];

printf("Enter the number of integers you want to add: ");
    scanf("%d", &n);

 printf("\n\nEnter %d integers \n\n", n);

for(c = 0; c < n; c++)
   {
        scanf("%d", &array[c]);
        sum =sum+array[c];    // same as sum = sum + array[c]
    }

  printf("\n\nSum = %d\n\n", sum);
    return 0;
}

```
<img src="https://i.imgur.com/NjD8NyP.png">

### 22) Program to add two matrices .
```C
/*  Addition of matrix */
    
#include <stdio.h>
 
int main() {
   
   int m, n, c, d, first[10][10], second[10][10], sum[10][10];
 
   printf("Enter the number of rows and columns of matrix\n");
   scanf("%d%d", &m, &n);
   
   printf("Enter the elements of first matrix\n");
 
   for (c = 0; c < m; c++)
      for (d = 0; d < n; d++)
         scanf("%d", &first[c][d]);
 
   printf("Enter the elements of second matrix\n");
 
   for (c = 0; c < m; c++)
      for (d = 0 ; d < n; d++)
         scanf("%d", &second[c][d]);
   
   printf("Sum of entered matrices:-\n");
   
   for (c = 0; c < m; c++) {
      for (d = 0 ; d < n; d++) {
         sum[c][d] = first[c][d] + second[c][d];
         printf("%d\t", sum[c][d]);
      }
      printf("\n");
   }
 
   return 0;
}

```
<img src="https://i.imgur.com/Qt9sy4i.png">

### 23) Program to multiply two matrices .
```C
/* Multiplation of matrices */
#include<stdio.h>
int main()
{
        int m,n,p,q,c,d,k,sum=0;
        int a[10][10],b[10][10],multiply[10][10];

                printf("enter number of rows and columns of first matrix\n");
                scanf("%d%d",&m,&n);
                printf("enter elements of first matrix\n");

        for(c=0;c<m;c++)
                 for(d=0;d<n;d++)
                        scanf("%d",&a[c][d]);
                printf("enter number of rows and columns of second matrix\n");
                scanf("%d%d",&p,&q);
                      
        if(n!=p)
        printf("the matrices can't be multiplied with each other\n");
        else
        {
                printf("enter elements of second matrix\n");

        for(c=0;c<p;c++)
                for(d=0;d<q;d++)
                scanf("%d",&b[c][d]);

                        for(c=0;c<m;c++)
                        { for(d=0;d<q;d++)
                                { for(k=0;k<p;k++)
                                        {
                                                sum = sum+a[c][k]*b[k][d];
                                        }
                                  multiply[c][d]=sum;
                                   sum=0;
       
                                }
                        }
        printf("Product of the matrices :\n");
        for(c=0;c<m;c++)
                {
                        for(d=0;d<q;d++)
                        printf("%d \t",multiply[c][d]);

                        printf("\n");
                        }
                }               
                                        
return 0;                                       
}                                       
 
```
<img src="https://i.imgur.com/XNR76F1.png">

### 24) Program to check whether  a string is palindrome or not .
```C
#include<stdio.h>
#include <string.h>
 
int main() {
    char s[1000];
    int i,n,c=0;
 
   printf("Enter  the string : ");
   gets(s);
   n=strlen(s);
 
for(i=0;i<n/2;i++)
    {
    	if(s[i]==s[n-i-1])
    	c++;
 
 	}
if(c==i)
 	    printf("string is palindrome \n");
    else
        printf("string is not palindrome \n");
 
return 0;
}

```
<img src="https://i.imgur.com/hgnW0GS.png">

### 25) Program to perform basic operations like lenghth of string ,string concat, string copy ,string compare and string reverse.
```C
/*Fundamental string operation, lenth, concatenation, compare and copy strings without string.h */

#include <stdio.h> 
#include <stdlib.h>
  
int find_length(char string[]) {
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
<img src="https://i.imgur.com/1TrUezs.png">

### 26) Programs to swap two numbers using call by value and call by refernce.
```C
/* Call by reference */

#include <stdio.h>
void swap(int*, int*);
 
int main() {
   
   int x, y;
 
   printf("Enter the value of x and y\n");
   scanf("%d%d",&x,&y);
 
   printf("Before Swapping\nx = %d\ny = %d\n", x, y);
 
   swap(&x, &y); 
 
   printf("After Swapping\nx = %d\ny = %d\n", x, y);
 
   return 0;
}
 
void swap(int *a, int *b)
{
   int temp;
 
   temp = *b;
   *b = *a;
   *a = temp;
}
```
<img src="https://i.imgur.com/MrETglI.png">

### call by value:- 
```C
/* Call by value */

#include <stdio.h>
 
void swap(int, int);
 
int main() {
   
   int x, y;
 
   printf("Enter the value of x and y\n");
   scanf("%d%d",&x,&y);
 
   printf("Before Swapping\nx = %d\ny = %d\n", x, y);
 
   swap(x, y); 
 
   printf("After Swapping\nx = %d\ny = %d\n", x, y);
 
   return 0;
}
 
void swap(int a, int b) {
   int temp;
 
   temp = b;
   b = a;
   a = temp;
    printf("Values of a and b is %d  %d\n",a,b);
}
```
   
### 27) Program to calculate factorial of a number with and without recursion both.
```C
/* Recursion */

#include<stdio.h>
long int multiplyNumbers(int n);
int main() {
    
int n;
    printf("Enter a positive integer: ");
    scanf("%d", &n);
    printf("Factorial of %d = %ld", n, multiplyNumbers(n));
    return 0;
}
long int multiplyNumbers(int n)
{
    if (n >= 1)
        return n*multiplyNumbers(n-1);
    else
        return 1;
}
```
<img src="https://i.imgur.com/whUpb1M.png">

```C
/* Without recrsion: */

#include <stdio.h>

int main() {
  
  int c, n, fact = 1;
 
  printf("Enter a number to calculate its factorial\n");
  scanf("%d", &n);
 
  for (c = 1; c <= n; c++)
    fact = fact * c;
 
  printf("Factorial of %d = %d\n", n, fact);
 
  return 0;
}
```
### 28) Program to print fibonacci series with and without recursion both.
```C
/* Program to print fibonaci series with recursion */

#include<stdio.h>
void series(int);		//prototype

int main() {

  int n;

printf("\n\nEnter the number of terms you wish.......");
  scanf("%d",&n);
  printf("\n\n");

  series(n);			// function call
  printf("\n\n\n");

  return 0;
}

void series(int n)		// definition

{
   int t1=0,t2=1,next;

   for(int i=0;i<=n;i++)
  {
    printf("%d\t",t1);

    next=t1+t2;
    t1=t2;
    t2=next;
  }
}


```
<img src="https://i.imgur.com/BYBzV8v.png">

#
```C
// Fibonaci series without  recursion:-
#include <stdio.h>
int fibo(int);
 
int main() {

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
<img src="">

### 29) Program to calculate average of 5 numbers using function.
```C
 /* program to find average of 5 numbers  */
 
#include<stdio.h>
int avg(int,int,int,int,int);      // prototype
 
int main() { int a1,a2,a3,a4,a5,res;
   
   printf("\nEnter the numbers respectiively....");
   scanf("%d%d%d%d%d",&a1,&a2,&a3,&a4,&a5);
   
   res=avg(a1,a2,a3,a4,a5);     // function call
   printf("Average of the numbers %d",res);
   
   return 0; 
 }
 
 int avg(int a1,int a2,int a3,int a4,int a5)      // definition
 
 { int p; 
   p=(a1+a2+a3+a4+a5)/5;
   return p;
 }

```
<img src="https://i.imgur.com/Q1q4Ofd.png">

### 30) Program to implement linear search and binary.
 ```C
/* Program to implement linear search and Binary search */

#include <stdio.h>
int main()
{
int array[50] ,search,n,c;

printf("enter the number of elements in array\n");
scanf("%d",&n);

printf("enter %d integer(s) \n",n);

for(c=0;c<n;c++)
scanf("%d",&array[c]);

printf("enter a number to be searched\n");
scanf("%d",&search);

for(c=0;c<n;c++)    
        {
        if(array[c]==search)
                {
                        printf("%d is present at location %d.\n", search ,c+1);
        break;
                }

        }
if(c==n)
printf("%d isn't present in the array\n",search);

return 0;
}

```
<img src="https://i.imgur.com/ANAAACj.png">

### 31) Program to implement binary.
 ```C
#include<stdio.h>
int binarysearch(int arr[],int l,int r,int x)
{
        if (r>=1)
        { int mid=l+(r-1)/2;
        }
        if(arr[mid]==x)
        return mid;

        if (arr[mid]>x)
        return binarysearch(arr,l,mid-1,x);

        return binarysearch(arr,l,mid-1,x);
        }
        
        return -1;
 }

        int main(void)
{
        int arr[]={2,3,4,10,40};
        int n=sizeof(arr)/sizeof (arr[0]);
        int x=10;
        int result =binarysearch(arr,0,n-1,x);
        (result==-1); : printf("element is not present");
                     :printf("element is present at index %d",
                        result);
        return 0;
}
```
<img src="https://i.imgur.com/ANAAACj.png">

### 32) Program to implement bubble sort.
```C
   /* Bubble sort implementation  */
 
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
      if (array[d] > array[d+1]) /* For decreasing order use < */
      {
        swap       = array[d];
        array[d]   = array[d+1];
        array[d+1] = swap;
      }
    }
  }
 
  printf("Sorted list in ascending order:\n");
 
  for (c = 0; c < n; c++)
     printf("%d\n", array[c]);
 
  return 0;
}

```
<img src="https://i.imgur.com/dvQg0s2.png">

### 33) Program to store information of 10 students using array of structures.
```C
/* Structures for student */

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

<img src="https://i.imgur.com/nxw83jI.png">

### 34) Programs to compute the transpose of a matrix.
```C
#include<stdio.h>

int main()
{
        int a[10][10],transpose[10][10],r,c,i,j;
        printf("enter rows and columns of matrix:");
        scanf("%d%d",&r,&c);

        printf("\n Enter elements of matrix:\n");
        for(i=0;i<r;++i)
                for(j=0;j<c;++j)
                {
                printf("enter element a%d%d: ",i+1,j+1);
                scanf("%d",&a[i][j]);
                }

        printf("\n Entered Matrix: \n");
        for(i=0;i<r;++i)
                for(j=0;j<c;++j)
                 {
                        printf("%d  ",a[i][j]);

                        if(j==c-1)
                                printf("\n\n");
                }

                for(i=0;i<r;++i)
                        for(j=0;j<c;++j)
                        {
                                transpose[j][i]=a[i][j];
                        }

        printf("\nTranspose of Matrix :\n");
                for(i=0;i<c;++i)
                        for(j=0;j<r;++j)
                        {
                                printf("%d  ",transpose[i][j]);
                                if(j==r-1)
                                        printf("\n\n");
                        }
        return 0;               
}               


```
<img src="https://i.imgur.com/vqnNFuR.png">

### 35) Program to access array using pointer.
```C
#include <stdio.h>
int main()
{
   int data[5],i;
   printf("Enter elements: ");
   for(i = 0; i < 5; ++i)
     scanf("%d", data + i);
   printf("You entered: \n");
   for(i = 0; i < 5; ++i)
      printf("%d\n", *(data + i));
   return 0;
}

```
<img src="https://i.imgur.com/9MZAW0G.png">



