#include<stdio.h>

int main()
{
	int pos,ele;
	int arr[]={1,2,3,4,5,6,7,8};
	int n=sizeof(arr)/sizeof(arr[0]);
	printf("------Array----------\n");
	for(int i=0;i<n;i++)
	{
		printf("%d ",arr[i]);
	}
	printf("\n");
	
	printf("Enter the Element to Insert: ");
	scanf("%d",&ele);
	printf("Enter the position to Insert: ");
	scanf("%d",&pos);
	
	for(int i=n;i>=pos;i--)
	{
		arr[i]=arr[i-1];
	}
	
	arr[pos-1]=ele;
	
	n++;
	
	printf("---------New Array----------\n");
	
	for(int i=0;i<n;i++)
	{
		printf("%d ",arr[i]);
	}
	
}
