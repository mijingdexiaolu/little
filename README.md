# little
#include<stdio.h>
int main()
{
	int input = 0;
	printf("加入大厂\n");
	printf("你要好好学习吗? (1/0)");
	scanf("%d", &input);
	if(input == 1)
		printf("好offer\n");
	else
		printf("卖红薯\n");
	return 0;
}
