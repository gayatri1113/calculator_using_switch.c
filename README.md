//# calculator_using_switch.c//
#include<stdio.h>
int main()
{
    int n1,n2,i,add,sub,mul,div;
    printf("Enter first number\n");
    scanf("%d",&n1);
    printf("Enter second number\n");
    scanf("%d",&n2);
    printf("Enter 1 for addition\nenter 2 for subtraction\nenter 3 for multiplication\nenter 4 for division\n");
    scanf("%d",&i);
    if(i==1)
    {
        add=n1+n2;
        printf("addition=%d",add);
    }
    else if(i==2)
    {
        sub=n1-n2;
        printf("subtraction=%d",sub);
    }
    else if(i==3)
    {
        mul=n1*n2;
        printf("multiplication=%d",mul);
    }
    else
    {
        div=n1/n2;
        printf("division=%d",div);
    }

}
