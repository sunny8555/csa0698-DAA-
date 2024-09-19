//ArmStrong with Recursion

#include<stdio.h>
#include<math.h>

int countDigits(int n)
{    
       if(n==0)
       {
       	return 0;
	   }
	   else
	   {
	   	return 1+countDigits(n/10);
	   }
     	
}

int armStrong(int n,int digits)
{	if(n==0)
	{
		return 0;
	}
	return pow(n%10,digits)+armStrong(n/10,digits);
}

int main()
{
	int n;
	printf("Enter the Number: ");
	scanf("%d",&n);
	printf("No of Digits: ");
	int digits=countDigits(n);
	printf("%d",digits);
	printf("\n");
	int result=armStrong(n,digits);
	if(result==n)
	{
		printf("It is ArmStrong Number.");
	}
	else
	{
		printf("It is not ArmStrong Number.");
	}
	
}
