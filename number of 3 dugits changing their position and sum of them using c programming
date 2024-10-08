#include<stdio.h>
#include<conio.h>
int main ()
{
    int n,a,b,c,sum1,sum2,sum3,s1,s12,s2,s23;
    printf("Enter three digits number = ");
    scanf("%d",&n);
    a=n/100;
    b=(n%100)/10;
    c=n%10;
    printf("a = %d\nb = %d\nb = %d\n",a,b,c);
    if (a+b+c>=10){
        s1=a+b+c;
        sum1=s1%10;
        s12=s1/10;
        s2=a+b+c+s12;
        sum2=s2%10;
        s23=s2/10;
        sum3=a+b+c+s23;
    }
    else {
        sum1=a+b+c;
        sum2=a+b+c;
        sum3=a+b+c;
    }
    printf ("Changing position of the numbers ");
    printf("Sum = %d%d%d",sum3,sum2,sum1);
    getch () ;

}
