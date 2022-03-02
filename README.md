# little
int Add(int x,int y)
{
	int z = x+y;
	return z;
}
int main()
{
	int a = 10;
	int b = 20;
	int c = 0;
	int d = 90;
	int e = 100;
	c = Add(a,e);
	c = Add(d,e);
	c = Add(2,3);
	printf("c = %d\n",c);
	return 0;
}
