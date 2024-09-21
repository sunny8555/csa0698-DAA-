#include<stdio.h>
int main()
{
	int n,i,j,k;
	int min_index;
	int temp;
	int arr[100];
	printf("Enter the No of Elements: ");
	scanf("%d",&n);
	printf("-----Elements-------\n");
	for(i=0;i<n;i++)
	{
		printf("Enter the Element[%d]: ",i+1);
		scanf("%d",&arr[i]);
	}
	
	for(i=0;i<n;i++)
	{
		min_index=i;
		for(j=i+1;j<n;j++)
		{
			if(arr[j]<arr[min_index])
			{
				min_index=j;
			}
		}
		temp=arr[i];
		arr[i]=arr[min_index];
		arr[min_index]=temp;
		
		for(k=0;k<n;k++)
		{
			printf("%d, ",arr[k]);
		}
		printf("\n");
		
	}
	
	printf("-----Array in the Ascendiing ---\n");
	for(i=0;i<n;i++)
	{   
		printf("%d ",arr[i]);
	}
}
