#include<stdio.h>
#include<stdlib.h>

int binarySearch(int nums[],int l,int h,int k)
{  
    int mid;
	while(l<=h)
	{
		 mid=l+(h-l)/2;
		 if(nums[mid]==k)
		 {
		 	return mid;
		 }
		 if(nums[mid]<k)
		 {
		  l=mid+1;
		 }
		 else
		 {
		 	h=mid-1;
		 }
	}
	return -1;
}

int main()
{
	int i,n,k;
	printf("Enter No of Elements: ");
	scanf("%d",&n);
	int arr[n];
	printf("----------Enter Elements in Array---------\n");
	for(i=0;i<n;i++)
	{
		printf("Enter the Element[%d]: ",i+1);
		scanf("%d",&arr[i]);
	}
	printf("Enter the Element to Search: ");
	scanf("%d",&k);
	int result=binarySearch(arr,0,n-1,k);
	
	if(result==-1)
	{
		printf(" %d  Not found.",k);
	}
	else
	{
		printf("%d is found at %d ",k,result+1);
	}
	
	return 0;
}
