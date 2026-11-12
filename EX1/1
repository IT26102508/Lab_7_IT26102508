#include<stdio.h>
void calculate(int *x,int *y,int *z){
	int a= *x, b= *y, c= *z;

	*x=a + b + c;
	*y=a - b;
        *z=a * c;
}
int main (){
	int x,y,z;
	printf("Enter the first numbers (x y z):");
	scanf("%d %d %d",&x,&y,&z);
	calculate(&x,&y,&z);
	printf("Modified x : %d\n",x);
	printf("Modified y : %d\n",y);
	printf("Modified z : %d\n",z);

	return 0;

}
