 
<center><img src="https://i.imgur.com/EZtECRw.png"></center>

---

<h3><b>Guru Nanak Dev Engineering College
    ESC-18104/18105 Programming for Problem Solving</b>
  
  ---
     
     Name - Suhkpreet Singh Ubhi Branch - C.S.E Section - C2 Roll Number - 1915353 
    
<h3>
1.Program to print your name using puts:
</h3> 
 
```C
#include<stdio.h>
int main()
{
puts("My name is Sukhpreet Singh Ubhi");
return 0;
}
```
**Output:**
<img src="https://i.imgur.com/kZnq67p.png?1">
<h3>
2.To print College address:
</h3> 
 
```C
#include<stdio.h>
int main()
{
puts("Guru Nanak Dev Engineering College,");
puts("Gill Road,");
puts("Ludhiana,Punjab");
return 0;
}
```
**Output:**
<img src="https://i.imgur.com/2jPeoWk.png"
     height="150" width="150%">
<h3>
3.Program to add two integers:
</h3> 
 
```C
#include<stdio.h>
void main()
{
int a,b,c;
printf("enter numbers\n");
scanf("%d %d",&a,&b);
c=a+b;
printf("sum is %d\n",c);
}
```
**Output:**
<img src="https://i.imgur.com/hF0PQAl.png"
     height="150">
 <h3>
4.Program to compute quotient and remainder:
</h3> 
 
```C
#include<stdio.h>
int main()
{
int  n1,n2,q,r;
printf("enter first number ");
scanf("%d",&n1);
printf("enter second number ");
scanf("%d",&n2);
q=n1/n2;
r=n1%n2;
printf("The quotient is %d\n",q);
printf("The remainder is %d\n",r);
return 0;
}
 
```
**Output:**
<img src="https://i.imgur.com/Flb9VYc.png"
     height="110">
 <h3>
5.Program to swap two numbers without using third variable:
</h3> 
 
```C
#include<stdio.h>
void main()
{
int a,b;
printf("enter value of a ");
scanf("%d",&a);
printf("enter value of b ");
scanf("%d",&b);
a=a+b;
b=a-b;
a=a-b;
printf("swapped values are a=%d  b=%d ",a,b);
}
```
**Output:**
<img src="https://i.imgur.com/afWmj0q.png"
     height="110">
 <h3>
6.Program to check if number is even or odd:
</h3> 
 
```C
#include<stdio.h>
void main()
{
int num;
printf("enter the number ");
scanf("%d",&num);
if(num%2==0)
{
printf("number is even ");
}
else
{
printf("number is odd ");
}
}
```
**Output:**
<img src="https://i.imgur.com/vfLQ5b6.png?1" height="110">
<h3>
7.Program to find greater of two numbers:
</h3> 
 
```C
#include<stdio.h>
void main()
{
int num1,num2;
printf("enter two numbers ");
scanf("%d",&num1);
scanf("%d",&num2);
if(num1>num2)
{
printf("%d is greater ",num1);
}
else
{
printf("%d is greater ",num2);
}
}
```
**Output:**
<img src="https://i.imgur.com/zlHAiMj.png"
     height="110">
<h3>
8.Program to find greater of three numbers:
</h3> 
 
```C
#include<stdio.h>
void main()
{
int num1,num2,num3;
printf("enter first number ");
scanf("%d",&num1);
printf("enter second number ");
scanf("%d",&num2);
printf("enter third number ");
scanf("%d",&num3);
if((num1>num2)&&(num1>num3))
{
printf("%d is greater ",num1);
}
else if((num2>num1)&&(num2>num3))
{
printf("%d is greater ",num2);
}
else
{
printf("%d is greater ",num3);
}
}
```
**Output:**
<img src="https://i.imgur.com/zfXmWV5.png"
     height="120">
  <h3>
9.Program to find grade of student according to marks entered:
</h3> 
 
```C
#include<stdio.h>
int main()
{
int n;
printf("enter your percentge ");
scanf("%d",&n);
if(n>=90)
{
printf("A Grade\n");
}
else if((n>=70)&&(n<90))
{
printf("B Grade\n");
}
else
{
printf("C Grade");
}
return 0;
}
```
**Output:**
<img src="https://i.imgur.com/Lbhyl9t.png"
     height="120">
     <h3>
10.Program to find roots of quadratic equation:</h3> 
 
```C
#include<stdio.h>
#include<math.h>
void main()
{
int a,b,c;
float root1,root2;
printf("enter value of a ");
scanf("%d",&a);
printf("enter value of b ");
scanf("%d",&b);
printf("enter value of c ");
scanf("%d",&c);
int disc;
disc=b*b-4*a*c;
if(disc<0)
{
printf("Roots does not exist \n");
}
else if(disc==0)
{
root1=-b/(2*a);
root2==root1;
}
else
{
root1=(-b+sqrt(disc))/(2*a);
root2=(-b-sqrt(disc))/(2*a);
}
printf("Roots of quadratic equation are %f  %f\n",root1,root2);
}
```
**Output:**
<img src="https://i.imgur.com/QO776UH.png"
     height="120">
     <h3>
   11.Program to check if year is leap or not:</h3> 
 
```C
#include<stdio.h>
void main()
{
long int yr;
printf("enter the year ");
scanf("%d",&yr);
if(yr%4==0)
{
printf("%d is leap year ",yr);
}
else
{
printf("%d is not leap year ",yr);
}
}
```
**Output:**
<img src="https://i.imgur.com/nFYZa0Z.png"
     height="120">
 <h3>
12.Program to print table of 5:
</h3> 
 
```C
#include<stdio.h>
void main()
{
int  n=5;
for(int i=1;i<=10;i++)
{
printf("%d*%d=%d\n",n,i,n*i);
}
}
```
**Output:**
<img src="https://i.imgur.com/PAGddx6.png"> 
<h3>
13.Program to make calculator using switch case:
</h3> 
 
```C
#include<stdio.h>
int main()
{
int a,b;
char o;
printf("enter +,-,* or / ");
scanf("%c", &o);
printf("enter first number ");
scanf("%d",&a);
printf("enter second number ");
scanf("%d",&b);
switch(o)
{
case'+':
printf("sum is %d ",a+b);
break;
case'-':
printf("subtraction is %d ",a-b);
break;
case'*':
printf("multiplication is %d ",a*b);
break;
case'/':
printf("division is %d ",a/b);
break;
default:
printf("error\n");
}
return 0;
}
```
**Output:**<br>
<img src="https://i.imgur.com/hasJZQN.png"
     height="150"> 
<h3>
14.Program to calculate reverse of a number:
</h3> 
 
```C
#include<stdio.h>
int main()
{
int n,remainder,reverse=0;
printf("enter the number ");
scanf("%d",&n);
while(n!=0)
{
remainder=n%10;
reverse=reverse*10+remainder;
n=n/10;
}
printf("reversed number is %d\n",reverse);
return 0;
}
}
```
**Output:**
<img src="https://i.imgur.com/1iQ0jTA.png"
     height="150">
<h3>
15.Program to check if a number is palandrome or not:
</h3> 
 
```C
#include<stdio.h>
void main()
{
int n,remainder,reverse=0,originalnum;
printf("enter number ");
scanf("%d",&n);
originalnum=n;
while(n!=0)
{
remainder=n%10;
reverse=reverse*10+remainder;
n=n/10;
}

if(originalnum==reverse)
{
printf("%d is a palandrome\n", reverse);
}
else
{
printf("%d is not a palandrome\n", reverse);
}
}
```
**Output:**
<img src="https://i.imgur.com/IWPQ5fi.png"
     height="150"> 
<h3>
16.Program to check if a number is prime or not:
</h3> 
 
```C
#include<stdio.h>
void main()
{
int num,prime,flag;
printf("Enter the Number ");
scanf("%d",&num);
if(num==1)
{
printf("1 is neither prime nor composite");
}
if(num%2==0)
{
flag=0;
}
else
{
flag=1;
}
if(flag==1)
{
printf("%d is prime ",num);
}
else
{
printf("%d is composite ",num);
}
}
```
**Output:**
<img src="https://i.imgur.com/YEaX5g4.png"
     height="150">
<h3>
17.Program to print prime numbers from 1 to 100:
</h3> 
 
```C
#include<stdio.h>

int main()
{
int numbr,k,remark;
printf(" The prime numbers between 1 and 100 : \n");
for(numbr=2;numbr<=100;++numbr)
{
remark=0;
for(k=2;k<=numbr/2;k++){
if((numbr % k) == 0){
remark++;
break;
}
}
if(remark==0)
printf("\n    %d ",numbr);
}
return 0;
}
```
**Output:**<br>
<img src="https://i.imgur.com/juP5Xdt.png"
     height="190">
<h3>
18.Program to check whether a number is armstrong or not:
</h3> 
 
```C
#include <stdio.h>
#include <math.h>
int main()
{
    int number, originalNumber, remainder, result = 0, n = 0 ;
    printf("Enter an integer: ");
    scanf("%d", &number);
     originalNumber = number;
    
    while (originalNumber != 0)
    {
        originalNumber /= 10;
        ++n;
    }
    originalNumber = number;
    while (originalNumber != 0)
    {
        remainder = originalNumber%10;
        result += pow(remainder, n);
        originalNumber /= 10;
    }
    if(result == number)
        printf("%d is an Armstrong number.\n", number);
    else
        printf("%d is not an Armstrong number.\n", number);
    return 0;
}
```
**Output:**
<img src="https://i.imgur.com/Kk5W5fV.png"
     height="150">
<h3>
19.Program to generate different number patterns:
</h3> 
<h4>
    A.
</h4>
 
```C
#include<stdio.h>
void main()
{
for(int i=1;i<=5;i++)
{
for(int j=1;j<=i;j++)
{
printf("%d",j);
}
printf("\n");
}
}
```
**Output:**
<img src="https://i.imgur.com/1hyZ9QC.png"
     height="150">
<h4>
B.
</h4> 
 
```C
#include <stdio.h>
int main()
{
int i, j, N,value;
value = 1;
printf("Enter rows: ");
scanf("%d", &N);
for(i=1; i<=N; i++)
{
  for(j=1;j<=i;j++)
    {
     printf("%d ", value);
     value++;
    }

     printf("\n");

     }

    return 0;
}
```
**Output:**
<img src="https://i.imgur.com/Zm2k9hW.png"
     height="150">
<h4>
C.
</h4> 
 
```C
#include<stdio.h>

void main()
{
        int i,n,j;
        
        printf("Enter the no of lines\n");
        scanf("%d",&n);
        
        for(i=1;i<=n;i++)
        {
            for(j=1;j<=n-i;j++)
            {
                printf(" ");
            }
            for(j=1;j<=i;j++)
            {
                printf("%d",j);
            }
            for(j=i-1;j>=1;j--)
            {
                printf("%d",j);
            }
            printf("\n");
        }
}
```
**Output:**
<img src="https://i.imgur.com/4y3x0UZ.png"
     height="150">
<h3>
20.Program to find largest element from one dimensional array:
</h3> 
 
```C
#include<stdio.h>
void main()
{
int arr[20];
int n;
int max;
int i;
printf("enter no. of array elements you want ");
scanf("%d",&n);
printf("enter array elements\n");
for(i=0;i<n;i++)
{
scanf("%d",&arr[i]);
}
max=arr[0];
for(i=0;i<n;i++)
{
if(arr[i]>max)
{
max=arr[i];
} 
}
printf("largest element in arry is %d\n",max);
}
```
**Output:**
<img src="https://i.imgur.com/bSXRg8T.png"
     height="150">
<h3>
21.Program to find sum of N natural numbers using array:
</h3> 
 
```C
#include<stdio.h>
int main()
{
int arr[100],num,sum=0,i;
printf("enter limit of natural numbers ");
scanf("%d",&num); 
for(i=1;i<=num;i++)
{
arr[i]=i;
sum=sum+arr[i];
}
printf("sum is %d\n",sum);
return 0;
}
```
**Output:**
<img src="https://i.imgur.com/8A3vmR2.png"
     height="150">
<h3>
22.Program to add two matrices:
</h3> 
 
```C
#include<stdio.h>
void main()
{
int a[3][3];
for(int i=1;i<=2;i++)
{
        for(int j=1;j<=2;j++)
        {
        printf("enter ");
        scanf("%d",&a[i][j]);
        }
}
int b[3][3];
printf("\n");
for(int k=1;k<=2;k++)
{
        for(int l=1;l<=2;l++)
        {
        printf("enter ");
        scanf("%d",&b[k][l]);
        }
}
int c[3][3];
for(int r=1;r<=2;r++)
{
        for(int t=1;t<=2;t++)
        {
        c[r][t]=a[r][t]+b[r][t];
        printf("%d   ",c[r][t]);
        }
printf("\n");
}
} 
```
**Output:**<br>
<img src="https://i.imgur.com/MxvNrBK.png"
     height="150">
<h3>
23.Program to multiply two matrices:
</h3> 
 
```C
#include<stdio.h>
void main()
{       
int a[3][3];
for(int i=1;i<=2;i++)
{
        for(int j=1;j<=2;j++)
        {
        printf("enter ");
        scanf("%d",&a[i][j]);
        }
}       
int b[3][3];
printf("\n");
for(int k=1;k<=2;k++)
{
        for(int l=1;l<=2;l++)
        {
        printf("enter ");
        scanf("%d",&b[k][l]);
        }
}
int c[3][3];
for(int r=1;r<=2;r++)
{
        for(int t=1;t<=2;t++)
        {
        c[r][t]=a[r][t]+b[r][t];
        printf("%d   ",c[r][t]);
        }
printf("\n");
}
}
```
**Output:**<br>
<img src="https://i.imgur.com/DBvWkVp.png"
     height="150">
<h3>
24.Program to check if string is palandrome or not:
</h3> 
 
```C
#include <stdio.h>
#include <string.h>

int main(){
    char string1[20];
    int i, length;
    int flag = 0;
    
    printf("Enter a string:");
    scanf("%s", string1);
    
    length = strlen(string1);
    
    for(i=0;i < length ;i++){
        if(string1[i] != string1[length-i-1]){
            flag = 1;
            break;
   }
}
    
    if (flag) {
        printf("%s is not a palindrome\n", string1);
    }    
    else {
        printf("%s is a palindrome\n", string1);
    }
    return 0;
}
```
**Output:**
<img src="https://i.imgur.com/NGmqMdz.png"
     height="150">
<h3>
25.Program to perform basic operations like length of string,string concat,string copy,string compare and string reverse:
</h3> 
 
```C
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
  string1[i] = '\0'; 
}   

  
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
  char string1[20], string2[20];
int choice;
  while (1) {
   printf("\n1. Find Length \n2. Concatenate \n3. Compare \n4. Copy \n5. Exit\n");
    printf("Enter your choice: ");
    scanf("%d",&choice);
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
      printf("String1 = %s\n",string1);
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
**Output:**
<img src="https://i.imgur.com/NNFuaCR.png"
     height="">
<h3>
26.Program to swap two numbers using call by value and call by reference:
</h3> 
 <h4>
    A.Call by value
</h4>

```C
#include<stdio.h>
void swap(int x,int y);
void main()
{
int a,b;
printf("enter value of a ");
scanf("%d",&a);
printf("\n");
printf("enter value of b ");
scanf("%d",&b);
printf("\n");
swap(a,b);
}
void swap(int x,int y)
{
int c;
if(x==y)
{
printf("swapped numbers are %d%d",x,y);
}
else
{
c=x;
x=y;
y=c;
printf("after swapping \n");
printf("value of a %d\n",x);
printf("value os b %d\n",y);
}
}
```
**Output:**
<img src="https://i.imgur.com/oOARsyf.png"
     height="150">
<h4>
    B.Call by reference
</h4>

```C
#include<stdio.h>
void swap(int *a,int *b);
void main()
{
int a,b;
printf("enter value of a ");
scanf("%d",&a);
printf("enter value of b ");
scanf("%d",&b);
swap(&a,&b);
printf("after swapping\nvalue of a=%d\nvalue of b=%d\n",a,b);
}
void swap(int *a,int *b)
{
int temp;
temp=*a;
*a=*b;
*b=temp;
}
```
**Output:**
<img src="https://i.imgur.com/puIKXnr.png"
     height="150">
     <h3>
27.Program to calculate factorial of a number with and without recursion:
</h3> 
<h4>
    A.Without 
Recursion
</h4>
 
```C
#include<stdio.h>
int fact(int m);
void main()
{
int a,func;
printf("enter the number ");
scanf("%d",&a);
func=fact(a);
printf("facorial is %d\n",func);
}
int fact(int m)
{
int sum=1;
        for(int i=1;i<=m;++i)
        {


                sum=sum*i;

        }
return sum;
} 
```
**Output:**
<img src="https://i.imgur.com/GU0CKj9.png"
     height="130">
     <h4>
    B.With Recursion
</h4>

```C
#include<stdio.h>
int fact(int n);
void main()
{
int n,result;
printf("enter the number ");
scanf("%d",&n);
result=fact(n);
printf("factorial is %d ",result);
}       
int fact(int n)
{
int val;
if(n==0)
{   
val=0;
}
else if(n==1)
{
val=1;
}
else
{
val=n*fact(n-1);
}
return val;
}
```
**Output:**
<img src="https://i.imgur.com/zxiqjxH.png"
     height="130">
  <h3>
28.Program to print fibbonaci series with and without recursion:
</h3> 
<h4>
    A.Without 
Recursion
</h4>
 
```C
#include <stdio.h>
int main()
{
    int t1 = 0, t2 = 1, nextTerm = 0, n;
    printf("Enter a positive number: ");
    scanf("%d", &n);
    printf("Fibonacci Series: %d, %d, ", t1, t2);
    nextTerm = t1 + t2;
    while(nextTerm <= n)
    {
        printf("%d, ",nextTerm);
        t1 = t2;
        t2 = nextTerm;
        nextTerm = t1 + t2;
    }
    
    return 0;
}
```
**Output:**<br>
<img src="https://i.imgur.com/amrzl39.png"
     height="130">
<h4>
    B.With 
Recursion
</h4>
 
```C
#include<stdio.h>
int fib(int n);
void main()
{
int n,result;;
printf("enter how many terms you want to print ");
scanf("%d",&n);
for(int i=0;i<n;i++)
{
printf("%d\n",fib(i));
}
}
int fib(int n)
{
if(n==0)
{   
return n;
}
else if(n==1)
{
return 1;
}
else
{
return(fib(n-1)+fib(n-2));
}
}
```
**Output:**
<img src="https://i.imgur.com/MMfSolx.png"
     height="130"> 
<h3>
29.Program to calculate average of five numbers using function:
</h3> 
 
```C
#include <stdio.h>
float average(int a, int b, int c, int d, int e){
    return (float)(a+b+c+d+e)/5;
}
int main()
{
    int num1, num2, num3, num4, num5;
    float avg;

    printf("Enter first number: ");
    scanf("%d",&num1);
    printf("Enter second number: ");
    scanf("%d",&num2);
   printf("Enter third number: ");
    scanf("%d",&num3);
    printf("Enter fourth number: ");
    scanf("%d",&num4);
   printf("Enter fifth number: ");
    scanf("%d",&num5);
    

    
    avg = average(num1, num2, num3, num4, num5);

                                                                               
    printf("Average of 5 numbers is: %.2f\n",avg);
    return 0;
}   
```
**Output:**
<img src="https://i.imgur.com/r4ikFn6.png"
     height="130"> 
<h3>
30.Program to implement linear search and binary search:
</h3> 
<h4>
    A.Linear search
</h4> 

```C
#include <stdio.h>
 
int main()
{
  int array[100], search, c, n;
 
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
**Output:**<br>
<img src="https://i.imgur.com/LnnX9P0.png"
     height="130">
<h4>
    B.Binary Search
</h4>

```C
#include<stdio.h>
void main()
{       
int n,arr[20],search;
printf("enter  amount of numbers ");
scanf("%d",&n);
for(int i=0;i<n;i++)
{       
printf("enter values in array ");
scanf("%d",&arr[i]);
}       
printf("enter the element to search ");
scanf("%d",&search); 
int first=0;
int last=n-1;
int middle=(first+last)/2;
while(first<=last)
{
        if(search>arr[middle])
        {
        first=first+1;
        }
        else if(search==arr[middle])
        {
        printf("element found at %drd position \n",middle+1);
        break;
        }
        else
        {
        last=last-1;
        }
middle=(first+last)/2;
}if(first>last)
{
printf("element not found ");
}       
} 
```
**Output:**
<img src="https://i.imgur.com/0xAs8u7.png"
     height="130">
     <h3>
 31.Program to implement bubble sort:
</h3> 
 
```C
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
**Output:**<br>
<img src="https://i.imgur.com/B0Pc0Je.png"
     height="130"> 
<h3>
32.Program to store information of 10 students using array of structures:
</h3> 

```C
#include<stdio.h>
struct student
{
char name[20];
int age;
char gender[10];
};
void main()
{
struct student st[12];
for(int i=1;i<=10;i++)
{
printf("enter name ");
scanf("%s",&st[i].name);
printf("enter age ");
scanf("%d",&st[i].age);
printf("enter gender ");
scanf("%s",&st[i].gender);
printf("\n\n");
}
for(int j=1;j<=10;j++)
{
printf("%s\n%d\n%s",st[j].name,st[j].age,st[j].gender);
printf("\n\n");
}
}
```
**Output:**
<img src="https://i.imgur.com/w6JZnEm.png?1">
<h3>
33.Program to compute transpose of matrice:
</h3> 

```C
#include<stdio.h>
int main()  
{       
    int a[10][10], transpose[10][10], r, c, i, j;
    printf("Enter rows and columns of matrix: ");
    scanf("%d %d", &r, &c);
    printf("\nEnter elements of matrix:\n");
    for(i=0; i<r; i++)
        for(j=0; j<c; j++)
        {
            printf("Enter element a%d%d: ",i+1, j+1);
            scanf("%d", &a[i][j]);
        }
    printf("\nEntered Matrix: \n");
    for(i=0; i<r; i++)
    {       
        for(j=0; j<c; j++)
        {
            printf("%d  ", a[i][j]);
        }
        printf("\n\n");
    }
        for(i=0; i<r; i++)
        for(j=0; j<c; j++)
        {
            transpose[j][i] = a[i][j];
        }
    printf("\nTranspose of Matrix:\n");
    for(i=0; i<c; i++)
        for(j=0; j<r; j++)
        {
            printf("%d  ",transpose[i][j]);
            if(j==r-1)
              printf("\n\n");
        }
    return 0;
}       
 
```
**Output:**
<img src="https://i.imgur.com/T6ldC3T.png">
<h3>
34.Program to print the address of variable using pointer: 
</h3> 

```C
#include<stdio.h>
void main() 
{ 
int *p; int q=5;
p=&q;
printf("address of variable is %d\n",p);
}
```
**Output:**
<img src="https://i.imgur.com/QgRk8p8.png"
     height="120">
<h3>
35.Program to access array elements using pointer: 
</h3> 

```C
#include<stdio.h>
void main()
{
int p[10];
int *q;
q=p;
printf("enter array elements\n");
for(int i=0;i<4;i++)
{
scanf("%d",&p[i]);
}
printf("array elements are\n");
for(int i=0;i<4;i++)
{
printf("%d\n",q[i]);
}
printf("\n");
}
```
**Output:**
<img src="https://i.imgur.com/x6I7LBQ.png"
     >












































