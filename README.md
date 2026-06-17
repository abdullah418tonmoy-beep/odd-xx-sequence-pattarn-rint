// hudai important na . amar failour project

#include<stdio.h>
int main()
{
    int n,m,i,j;
    scanf("%d",&n);
int a=1;

    for(i=1;i<n;i+=2)
    {
        for(j=1;j<=n;j++)
        {

            printf("%d ",a);
            a+=2;

        }
        printf("\n");
    }
    return 0;

}
