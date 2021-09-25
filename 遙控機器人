//
//  main.c
//  HW W9-1-2
//
//  Created by 孫渝鈞 on 2020/11/6.
//  Copyright © 2020 孫渝鈞. All rights reserved.
//

#include<stdio.h>
#include<string.h>


int main(){
    
    int x,y;
    scanf("%d %d",&x,&y);
        
        char A[x][y];
        
        for(int i=0;i<x;i++){
            for(int j=0;j<y;j++){
              scanf(" %c",&A[i][j]);
                        
            }
        }

   int a,b;
   scanf("%d %d",&a,&b);
       
   char str[20000];
   scanf("%s",str);
        
        
    
        for(int k=0;k<strlen(str);k++){
            
            
            
            if(str[k]=='R'){
                if(A[a][b+1]=='.'&&b<y-1) {
                        b=b+1;
                }
            }
            if(str[k]=='L'){
                if(A[a][b-1]=='.'&&b>0){
                        b=b-1;
                }
            }
            if(str[k]=='U'){
                if(A[a-1][b]=='.'&&a>0){
                        a=a-1;
                }
                     
            }
            if(str[k]=='D'){
                if(A[a+1][b]=='.'&&a<x-1){
                    a=a+1;
                }
                   
            }
        
        }
        
    
    printf("%d",a);
    printf(" ");
    printf("%d",b);
    printf("\n");
    
    
    return 0;
    
}

