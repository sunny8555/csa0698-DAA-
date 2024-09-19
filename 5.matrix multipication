#include<stdio.h>
#include<time.h>

void multiplication(int nums1[][10],int nums2[][10],int n)
{
	int i,j,k;
	int mul[10][10];
	for(i=0;i<n;i++)
	{
		for(j=0;j<n;j++)
		{  
			mul[i][j]=0;
			for(k=0;k<n;k++)	
			{
				mul[i][j]+= nums1[i][k]  *  nums2[k][j];
			}
		}
	}
	printf("----------Multiplication of Matix--------\n");
	
	for(i=0;i<n;i++)
	{
		for(j=0;j<n;j++)
		{
			printf("%d ",mul[i][j]);
		}
		printf("\n");
	}
}


int main()

{
	int i,j,k;
	int n;
	int arr1[10][10],arr2[10][10];
	printf("Enter the No of Rows and Columns: ");
	scanf("%d",&n);
	printf("----Enter the Elements for Array 1-----\n");
	
	for(i=0;i<n;i++)
	{
		for(j=0;j<n;j++)
		{
			scanf("%d",&arr1[i][j]);
		}
	}
		printf("----Enter the Elements for Array 2-----\n");
	
	for(i=0;i<n;i++)
	{
		for(j=0;j<n;j++)
		{
			scanf("%d",&arr2[i][j]);
		}
	}
	
	clock_t start=clock();
	
	multiplication(arr1,arr2,n);
	clock_t end=clock();
	
	printf("Time Complexity of Matrix Mutliplication is : %1d ",end-start);
}
