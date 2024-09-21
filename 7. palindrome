#include<stdio.h>
#include<string.h>

int isPolindrome(char str[],int start,int end)
{
	if(start>=end)
	{
		return 1;
	}
	if(str[start]!=str[end])
	{
		return 0;
	}
	
	return isPolindrome(str,start+1,end-1);
}
int main()
{
	char str[100];
	int i;
	printf("Enter the String: ");
	scanf("%s",str);
	int len=strlen(str);
	if(isPolindrome(str,0,len-1))
	{
		printf(" %s is Polindrome.",str);
	}
	else
	{
		printf(" %s is not Polindrome.",str);
	}
	
}
