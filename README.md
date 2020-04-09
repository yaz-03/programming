#include <stdio.h>

int main()
{
    int a,b;
    printf("enter two numbers a and b");
    scanf("%d",&a);
    scanf("%d",&b);
    printf("before swapping %d and %d",a,b);
    a=a+b;
    b=a-b;
    a=a-b;
    printf("after swapping %d and %d",a,b);
}
