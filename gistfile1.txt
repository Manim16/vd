#include <stdio.h>
#define N 10000
int main()
{
    int n,m,n1,n2,c,f;
    printf("n:");
    scanf("%d",&n);
    printf("m:");
    scanf("%d",&m);
    printf("n1:");
    scanf("%d",&n1);
    printf("n2:");
    scanf("%d",&n2);
    c=(n-m)+n1*m;
    f=(n-m)+n2*m;
    int s[N];
    for (int i=c;i<=f;i=i+m)
    {
        s[i]=i;
        printf("%d ",s[i]);
    }

    return 0;
}
