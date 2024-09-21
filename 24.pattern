#include<stdio.h>
void printNumbers(int n)

{
	if(n==0)
	{
		return ;
	}
	printNumbers(n-1);
	printf("%d ",n);
}
void pattern(int n,int current)
{
	if(current>n)
	{
		return;
	}
	printNumbers(current);
	printf("\n");
	pattern(n,current+1);
}

int main()
{
	int n=4;
	pattern(n,1);
}
