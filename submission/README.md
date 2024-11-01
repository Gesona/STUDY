#include<stdio.h>
int main()
{
    int str[11];
    int i,j,b;
    for(j=1;j＜11;j++)
  {
        scanf_s("%d",&str[j]);
  }

    for(i=1;i＜=10-i;i++)
  {
        for(j=1;j＜=10-i;j++)
      {            
            if(str[j]＞=str[j+1])
           {
            b=str[j];
            str[j]=str[j+1];
            str[j+1]=b;
           }
      }
  }
  for(j=1;j＜11;j++)
  printf("%d\n",str[j]);
}
