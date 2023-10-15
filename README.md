# Sum_bet_two_num
#include<stdio.h>
void main()
{
int n,sum=0;
printf("enter first number :-");
scanf("%d",&n);
int m;
printf("enter second number :-");
scanf("%d",&m);

for (int i=n;i<=m;i++)
{
sum+=i;
}
printf("%d",sum);



}
