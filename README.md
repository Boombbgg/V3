#include<stdio.h>
int main()
{
	char str[]="2+2*3+2/2-1";
	int sum,a,b,c,d;
	a=str[0]-'0';
	b=(str[2]-'0')*(str[4]-'0');
	c=(str[6]-'0')*(str[8]-'0');
	d=str[10]-'0';
	sum=a+b+c-d;
	printf("%d\n",sum);
	return 0;

}
