#include<stdio.h>
#include<stdlib.h>
#include<string.h>
void copyString(char *initial,char *final,int index)
{
	if(initial[index]=='\0')
	{
		final[index]='\0';
		return ;
		
	}
	final[index]=initial[index];
	copyString(initial,final,index+1);
	
}

int main()
{
	char initial[500],final[500];
	printf("Enter the String: ");
	scanf("%s",initial);
	copyString(initial,final,0);
	printf("%s is the Copied String.\n",final);
	return 0;
}
