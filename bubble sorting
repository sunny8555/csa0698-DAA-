#include<stdio.h>
int main()
{
	int arr[100],i,j,k;
	int n;
	int temp;
	printf("Enter no of Elements: ");
	scanf("%d",&n);
	printf("--------Array--------\n");
	for(i=0;i<n;i++)
	{
		printf("Enter the Element[%d]: ",i+1);
		scanf("%d",&arr[i]);
	}
	
	for(i=0;i<n-1;i++)
	{
		for(j=0;j<n-i-1;j++)
		{
			if(arr[j]>arr[j+1])
			{
				temp=arr[j];
				arr[j]=arr[j+1];
				arr[j+1]=temp;
			}
		}
		for(k=0;k<n;k++)
		{
			printf("%d ",arr[k]);
		}
		printf("\n");
		
	}
	
	printf("------Bubble Sorting------\n");
	for(i=0;i<n;i++)
	{
		printf(" %d ",arr[i]);
	}
	
}
