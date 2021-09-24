//
//  main.c
//  HW W5-3
//
//  Created by 孫渝鈞 on 2020/10/2.
//  Copyright © 2020 孫渝鈞. All rights reserved.
//

#include <stdio.h>

int main()
{
    int n,m,o,i,k;
    scanf("%d %d",&n,&m);  //4 5
    o=14;
    o=o+(m-1)*4;
    for(i=0;i<o;i++){
        (i==0||i==6||i==o-1)?printf("+"):printf("-");
    }
    printf("\n");
    printf("|");
    printf("%6s","|");
    
   
    for(i=1;i<=m;i++){
    if(i==m){
        printf("%4d",i);
        printf("%3s","|");
        printf("\n");
        }
    else{
        printf("%4d",i);
    }
    }
    for(i=0;i<o;i++){
        (i==0||i==6||i==o-1)?printf("+"):printf("-");
    }
    printf("\n");
    printf("|");
    k=1;
    while(k<=n){
        if(k<n){
            printf("%3d",k);
            printf("%3s","|");
            for(i=1;i<=m;i++){
                if(i==m){
                printf("%4d",k*m);
                printf("%3s","|");
                    printf("\n");
                }else{
                    printf("%4d",k*i);
                    
                }
                
            }printf("|");
            
        }
        else{
                 printf("%3d",k);
                   printf("%3s","|");
                   for(i=1;i<=m;i++){
                       if(i==m){
                       printf("%4d",k*m);
                       printf("%3s","|");
                           printf("\n");
                       }else{
                           printf("%4d",k*i);
                           
                       }
                       
                   }
            }
            
        k++;
    }
    
    for(i=0;i<o;i++){
        (i==0||i==6||i==o-1)?printf("+"):printf("-");
    }
    
return 0;
}
