#include<stdio.h>
int findlcm(int, int);
int main()
{
	int a,b, lcm;
	printf("Enter two number: ");
	scanf("%d%d",&a,&b);
	lcm=findlcm(a,b);
	printf("Lcm of %d and %d is %d",a,b,lcm);
}
int findlcm(int a, int b)
{
	static int temp=1;
	if(temp%a==0 && temp%b==0)
	{
		return temp;
		
	}
	else
	{
		temp++;
		findlcm(a,b);
		return temp;
	}
}
