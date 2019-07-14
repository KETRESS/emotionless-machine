#include<stdio.h>
int main(void)
{   
	int max4(inta, intb, intc, intd);
	int a, b, c, d, max;
	printf("enter:");
	scanf("%d %d %d %d",&a,&b,&c,&d);
	max= max4(a, b, c, d);
	printf("max=%d\n",max);
	return 0;
}	
