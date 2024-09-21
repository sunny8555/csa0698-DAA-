#include<stdio.h>

int main()
{
	int volume=100;
	int volumes[]={30,40,20,50,10};
	int size=sizeof(volumes)/sizeof(volumes[0]);
	int totalVolume=0;
	
	for(int i=0;i<size;i++)
	{
		if(totalVolume+volumes[i]<=volume)
		{
			totalVolume+=volumes[i];
			printf("%d is Loaded into Container\n",volumes[i]);
		}
	}
	printf("Total Capacity Loaded is:%d",totalVolume);
}
