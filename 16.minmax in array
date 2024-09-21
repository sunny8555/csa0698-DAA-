#include<stdio.h>
#include<stdlib.h>

void minMax(int nums[],int n,int *min,int *max)
{
	*min=*max=nums[0];
	for(int i=0;i<n;i++)
	{
		if(nums[i]<*min)
		{
			*min=nums[i];
		}
		if(nums[i]>*max)
		{
			*max=nums[i];
		}
	}
}

int main()
{
	int arr[100];
	int n,i;
	printf("Enter No of Elements: ");
	scanf("%d",&n);
	printf("--------Enter the Array Elements----\n");
	for(i=0;i<n;i++)
	{
		printf("Enter the Element[%d]: ",i+1);
		scanf("%d",&arr[i]);
		
	}
	int min,max;
	
	minMax(arr,n,&min,&max);
	printf("Max Element is %d.\n",max);
	printf("Min Element is %d.\n",min);
	return  0;
	
}
