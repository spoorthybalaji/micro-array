# micro-array
Micro and Array Update
Micro purchased an array A having N integer values. After playing it for a while, he got
bored of it and decided to update value of its element. In one second he can increase
value of each array element by 1. He wants each array element's value to become greater
than or equal to K. Please help Micro to find out the minimum amount of time it will take,
for him to do so.

#include<stdio.h>
int main()
{
    int m,n,i,min=10000000000,k;
    scanf("%d",&m);
    while(t--)
    {
     min=10000000000;
     scanf("%d%d",&n,&k);
     int a[n];
     for(i=0;i<n;i++)
     {
      scanf("%d",&a[i]);
      if(a[i]<min)
       min=a[i];
     }
     //printf("%d ",min);
     if(min>=k)
      printf("0\n");
     else
      printf("%d\n",k-min);
    }
    return 0;

}


