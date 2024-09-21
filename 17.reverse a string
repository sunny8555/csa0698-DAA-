#include<stdio.h>
#include<string.h>
void reverseString(char *initial,char *final,int n,int i)
{    
	 if(n<0)
	{
		return;
	}
	final[i]=initial[n];
	reverseString(initial,final,n-1,i+1);
}
	
int main()
{
	char initial[500],final[500];
	printf("Enter the String: ");
	scanf("%s",initial);
	int n=strlen(initial);
	reverseString(initial,final,n-1,0);
	printf("%s is reverse String.\n",final);
}
