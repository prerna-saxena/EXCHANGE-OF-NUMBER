# EXCHANGE-OF-NUMBER
EXCHANGE OF NUMBER WITHOUT USING THIRD VARIABLE

#include<stdio.h>
#include<conio.h>
void main()
{
int a,b;
printf("ENTER THE NUMBERS");
scanf("%d%d", &a,&b);
a=b;
b=a;
printf("%d%d", &a,&b);
}
