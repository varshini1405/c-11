# c-11
floyd's triangle
#include <stdio.h>

int main() {
    int n,i,j,count=1;
    printf("enter the row:");
    scanf("%d",&n);
    for(i=1;i<=n;i++){
        for(j=1;j<=i;j++){
                printf("%d",count++);
        }    
        printf("\n");
        
    }
return 0;
}
