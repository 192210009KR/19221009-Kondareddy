#include<stdio.h>
int main()
{
	int i,j,r,c,a[100][100],trans[100][100];
	printf("enter the rows:");
	scanf("%d",&r);
	printf("enter the coloumns:");
	scanf("%d",&c);
	printf("enter a matrix:");
	for(i=0;i<r;i++)
	{
		for(j=0;j<c;j++)
		{
			printf("\nenter the elements a%d%d:",i+1,j+1);
			scanf("%d",&a[i][j]);
		}
	}
	printf("\nEntered matrix:\n");
	for (i=0;i<r;i++)
	{
		for (j=0;j<c;j++)
		{
			printf("%d  ",a[i][j]);
			if (j== c-1)
				printf("\n");
		}
	}
	for(i=0;i<r;i++)
	{
		for(j=0;j<c;j++)
		{
			trans[j][i]=a[i][j];
		}
	}
	printf("\nTranspose of matrix:\n");
	for(i=0;i<c;i++)
	{
		for(j=0;j<r;j++)
		{
			printf("%d  ",trans[i][j]);
			if(j==r-1)
				printf("\n");
		}
	}
	return 0;
}
