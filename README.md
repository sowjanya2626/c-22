# c-22
Floyd's triangle 
#include <stdio.h>
int main() 
{
    int i,j,n,count=1;
    printf("enter the row of the matrix:");
    scanf("%d",&n);
    for(i=1;i<=n;i++){
        for(j=1;j<=i;j++){
                printf("%d",count++);
    }
        printf("\n");
    }
    return 0;
}
