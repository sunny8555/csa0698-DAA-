#include<stdio.h>


int linearSearch(int arr[],int size,int n)
{
	for(int i=0;i<size;i++)
	{
		if(arr[i]==n)
		{
			return i;
		}
	}
	return -1;
}
int main()
{
	int arr[]={1,2,3,4,5,6};
	int n;
	int size=sizeof(arr)/sizeof(arr[0]);
		printf("------Array----------\n");
	for(int i=0;i<size;i++)
	{
		printf("%d ",arr[i]);
	}
	printf("\n");
	printf("Enter the Element to Search: ");
	scanf("%d",&n);


	int result=linearSearch(arr,size,n);
	
	if(result==-1)
	{
		printf("Element Not Found.\n");
	}
	else
	{
		printf("%d is found at index number: %d.",n,result);
	}
}
