#include<stdio.h>
int main()
{
	int num;

	printf("Enter a number :");
	scanf("%d", &num);

	if (num % 6 == 0 && num % 7 == 0)
	{
		printf("The number is exactly divisible by both 6 and 7,\n");
	}
	else
	{
		printf("The number is not exactly divisible by both 6 anf 7.\n");
	}
	system("pause");

	return 0;

}