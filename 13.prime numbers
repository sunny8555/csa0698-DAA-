#include<stdio.h>
int checkPrime(int n,int i)
{
	if(n<=2)
	{
		return (n==2)?1:0;
	}
	if(n%i==0)
	{
		return 0;
	}
	if(i*i>n)
	{
		return 1;
	}
	return checkPrime(n,i+1);
}
void primes(int n)
{
	if(n>=2)
	{
		if(checkPrime(n,2))
		{
			printf("%d ",n);
		}
		primes(n-1);
	}
}

int main()
{
	int n;
	printf("Enter the NUmber: ");
	scanf("%d",&n);
	printf("Prime Numbers Upto %d: \n",n);
	primes(n);
}
