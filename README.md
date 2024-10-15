# C-program-to-verify-a-given-number-is-palindrome-or-not-
#include<stdio.h>
void main()
{
 int original_num,r=0,rem,num;
 printf("Enter the number");
 scanf("%d",&original_num);
 num=original_num;
 while(num>0)
 {
  rem=num%10;
  r=r*10+rem;
  num=num/10;
 }
 {
 if(original_num==r)
    printf("the number is palindrome number");
 else
    printf("the number is not a palindrome number");
}
}
