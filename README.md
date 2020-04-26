# Save-the-prisoner-c
#include <assert.h>
#include <limits.h>
#include <math.h>
#include <stdbool.h>
#include <stddef.h>
#include <stdint.h>
#include <stdio.h>
#include <stdlib.h>
#include <string.h>
int main()
{
    int t,n,m,s,i,r,ans;
    scanf("%d",&t);
    for(i=0;i<t;i++)
    {
        scanf("%d %d %d",&n,&m,&s);
        r=m%n;
        ans=(r+s-1)%n;
        if(ans==0){
            ans=n;
        }
        printf("%d\n",ans);
    }
}
