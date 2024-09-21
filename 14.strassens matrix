#include<stdio.h>
#include<stdlib.h>
void Strassen(int a[2][2],int b[2][2],int c[2][2])
{
	int p,q,r,s,t,u,v;
	p=(a[0][0])*(b[0][1]-b[1][1]);
	q=((a[0][0]+a[0][1])*b[1][1]);
	r=(a[1][0]+a[1][1])*b[0][0];
	s=a[1][1]*(b[1][0]-b[0][0]);
	t=(a[0][0]+a[1][1])*(b[0][0]+b[1][1]);
	u=(a[0][1]-a[1][1])*(b[1][0]+b[1][1]);
	v=(a[0][0]-a[1][0])*(b[0][0]+b[0][1]);
	c[0][0]=s+t-q+u;
	c[0][1]=p+q;
	c[1][0]=r+s;
	c[1][1]=t+p-r-v;
	
}

int main()
{
	int a[2][2]={
	{1,2},
	{3,4}
	};
	int b[2][2]={
	{5,6},
	{7,8}
	};
	int c[2][2];
	
	Strassen(a,b,c);
	printf("----Strassens Matrix---------------\n");
	for(int i=0;i<2;i++)
	{
		for(int j=0;j<2;j++)
		{
			printf("%d ",c[i][j]);
		}
		printf("\n");
	}
}
