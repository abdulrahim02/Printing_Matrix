# Printing_Matrix
Created by Abdulrahim Mulla


//Printing_Matrix
#include<stdio.h>
#include<stdlib.h>

int main()

{
	int a[5][5],r,c;
	
	printf("Enter the Matrix Elements : \n");
	for(r=0;r<3;r++)
	{
		for(c=0;c<3;c++)
		{
			scanf("%d",&a[r][c]);
		}
	}
	
	printf("The Matrix is as follows:  \n");
	for(r=0;r<3;r++)
	{
		for(c=0;c<3;c++)
		{
			 printf("%d	\t",a[r][c]);
		}
		printf("\n");
	}
	return 0;
}

