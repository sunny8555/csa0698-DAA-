#include<stdio.h>
#define INF 9999
#define v 4

void floydsWarshall(int graph[][v])
{
	int dist[v][v],i,j,k;
	//--------------
	for(i=0;i<v;i++)
	{
		for(j=0;j<v;j++)
		{
			dist[i][j]=graph[i][j];
		}
	}
	
	for(k=0;k<v;k++)
	{
		for(i=0;i<v;i++)
		{
			for(j=0;j<v;j++)
			{
				if(dist[i][k]+dist[k][j]<dist[i][j])
				{
					dist[i][j]=dist[i][k]+dist[k][j];
				}
			}
		}
	}
	
	printSolution(dist);
}

void printSolution(int dist[][v])
{
	printf("---------FloydsWarshall Algoritgm---------\n");
	for(int i=0;i<v;i++)
	{
		for(int j=0;j<v;j++)
		{
			if(dist[i][j]==INF)
			{
				printf("%7s","INF");
			}
			else
			{
				printf("%7d",dist[i][j]);
			}
			
		}
		
		printf("\n");
		
	}
}
int main()
{
	int graph[v][v] = {
	        {0, 5, INF, 10},
	        {INF, 0, 3, INF},
	        {INF, INF, 0, 1},
	        {INF, INF, INF, 0}
	    };	
	
	floydsWarshall(graph);   
	    
}
