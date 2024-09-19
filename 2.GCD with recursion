
#include<stdio.h>

int gcd(int a,int b)
{
	if(b==0)
	{
		return a;
	}
	else
	{
		return gcd(b,a%b);
	}
}

int main()
{
	int a,b;
	printf("Enter the Number-1: ");
	scanf("%d",&a);
	printf("Enter the Number-2: ");
	scanf("%d",&b);
	
	int result=gcd(a,b);
	printf("GCD of %d and %d is %d.",a,b,result);
}
