# array-sum
This is a program for addition of required numbers using arrays in c programming.




#include<stdio.h>
#include<conio.h>
void main()
{
	int n,a[n],i,sum=0;
	printf("Enter how many numbers to be added:");
	scanf("%d",&n);
	printf("Enter numbers:");
	for(i=1;i<=n;i++)
	{
		scanf("%d",&a[i]);
	}
	for(i=1;i<=n;i++)
	{
		sum=sum+a[i];
	}
	printf("Sum of n numbers is %d",sum);
}
