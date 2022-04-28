# 2022.4.28-在GitHub创建了第一个存储库
计算三角形面积
int main()
{
	int a,b,c,p,s;
	printf("请依次输入三个边长\n");
	scanf("%d,%d,%d", &a,&b,&c);
	if (a > b + c && b > a + c && c > a + b);
	{
		p = (a + b + c) / 2;
		s = p * (p - a) * (p - b) * (p - c);
		s = sqrt(s);
		printf("三角形的面积为%d\n", s);
	}
	else printf("这三个数不能组成三角形");
	return 0;
}

 
