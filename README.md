# C43
Hallow rightangle triangle 
#include<stdio.h>
int main()
{
    int n,j,i;
    printf("enter the row of matrix:");
    scanf("%d",&n);
    for(i=1;i<=n;i++){
       for(j=1;j<=i;j++){
         if(j==1 || i==j || i==n){
          printf("* "); 
       }else{
       printf("  ");
       }
    }
       printf ("\n");
     
    }   
    return 0;
}
