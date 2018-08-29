#include<stdio.h>
#include<math.h>
#include<stdlib.h>
main()
{
    int a,b,c,t,d;
    scanf("%d %d",&a,&b);
    if(a>=-1000000&&a<=1000000&&b>=-1000000&&b<=1000000)
    {
        c=a+b;
    }
    d=abs(c);
    if(d<1000)
        printf("%d",c);
    else if(d<1000000)
    {
        printf("%d,%d",c/1000,abs(c%1000));
    }
    else
    {
        t=c%1000000;
        printf("%d,%d,%d",c/1000000,abs(t/1000),abs(t%1000));
    }

}
