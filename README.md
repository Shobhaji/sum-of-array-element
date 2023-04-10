#include<stdio.h>
#include<conio.h>
int sum_array(int a[],int size);
void main()
{
int sum,a[5]={1,2,3,4,5};
sum=sum_array(a,5);
printf("Sum of all array element:%d",sum);
getch();
}
int sum_array(int a[],int n)
{
int sum=0,i;
for(i=0;i<n;i++){
sum =sum +a[i];
}
return sum;
}

