#include<stdio.h>
int main()
{
    int a,b; //declaration of two variables whose quotient is to be performed
    int quotient=1;
    printf("Enter the first number:");
    scanf("%d",&a);
    printf("Enter the second number:");
    scanf("%d",&b);
    quotient=a/b; //quotient of the two numbers performed
    printf("The quotient of the two numbers is: %d",quotient);
return 0;
}
