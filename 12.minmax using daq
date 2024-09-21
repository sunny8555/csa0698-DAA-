#include<stdio.h>
void findMinMax(int arr[],int l,int h,int*min,int *max)
{
	if(l==h)
	{
		*min=*max=arr[l];
		return;
	}
	if(h==l+1)
	{
		if(arr[l]>arr[h])
		{
			*max=arr[l];
			*min=arr[h];
		}
		else
		{
			*max=arr[h];
			 *min=arr[l];
		}
		return;
	}
	
	int mid=(l+h)/2;
	int min1,max1;
	findMinMax(arr,l,mid,min,max);
	findMinMax(arr,mid+1,h,&min1,&max1);
	if(min1<*min)
	{
		*min=min1;
	}
	if(max1>*max)
	{
		*max=max1;
	}
}
int main()
{
	int arr[]={3,5,7,2,8,-1,4,10,12};
	int n=sizeof(arr)/sizeof(arr[0]);
	int min,max;
	findMinMax(arr,0,n-1,&min,&max);
	printf("Maximum :%d \n",max);
	printf("Minimum :%d \n",min);
}
