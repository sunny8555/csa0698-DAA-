#include<stdio.h>

void factors(int n,int i)
{
	if(i<=n)
	{
		if(n%i==0)
		{
			printf("%d ",i);
		}
	}
	factors(n,i+1);
}
int main()
{
	int n;
	printf("Enter the Number: ");
	scanf("%d",&n);
	factors(n,1);
}
