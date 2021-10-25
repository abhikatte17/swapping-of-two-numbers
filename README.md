# swapping-of-two-numbers
Created by Abhishek Katte. Swapping of two numbers without using temporary variable
#include<stdio.h>

int main()
{
   int a=20, b=30;
   printf("Before swap a=%d b=%d",a,b);
   a=a+b;//a=50,(20+30)
   b=a-b;//b=20,(50-30)
   a=a-b;//a=30,(50-20)
   printf("\nAfter swap a=%d b=%d",a,b);
   return 0;
}
