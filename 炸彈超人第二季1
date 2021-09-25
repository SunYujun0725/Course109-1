//
//  main.c
//  HW W10-3
//
//  Created by 孫渝鈞 on 2020/11/10.
//  Copyright © 2020 孫渝鈞. All rights reserved.
//

#include <stdio.h>

int main()
{   int x,y;
    scanf("%d %d",&x,&y);
    char A[x][y];
    for(int i=0;i<x;i++){
        for(int j=0;j<y;j++){
            scanf(" %c",&A[i][j]);
        }
    }
    int z;
    scanf("%d",&z);
    int B[200000];
    int m=0;
    for(int i=0;i<x;i++){
      for(int j=0;j<y;j++){
            m++;
            if(A[i][j]=='.'){
                
                            
            for(int k=1;k<=z;k++){
                
                   if(A[i+k][j]=='#'||(i+k)>=x){
                       break;
                   }
                   else {
                       if(A[i+k][j]=='@'){
                           B[m]++;
                       }
                  }
            }
          
          }
           
        }
    }
    m=0;
      for(int i=0;i<x;i++){
         
          for(int j=0;j<y;j++){
            
              m++;
              if(A[i][j]=='.'){
      
                 
              for(int k=1;k<=z;k++){
                  
                     if(A[i-k][j]=='#'||(i-k)<0){
                        break;
                     }
                     else{
                        if(A[i-k][j]=='@'){
                         B[m]++;
                     }
                     }
                
              
             }
          
          
              }
      
          }
      }
    
    m=0;
         for(int i=0;i<x;i++){
          
             for(int j=0;j<y;j++){
                
                 m++;
                 if(A[i][j]=='.'){
             
           
                 for(int k=1;k<=z;k++){
                  
                        if(A[i][j+k]=='#'||(j+k)>=y){
                          break;
                         }
                        else {
                           if(A[i][j+k]=='@'){
                                B[m]++;
                            }
                        }
                     
                 }
                
                 }
             }
         }
    
    m=0;
         for(int i=0;i<x;i++){
             
             for(int j=0;j<y;j++){
                 
                 m++;
                 if(A[i][j]=='.'){
                   
            
                     for(int k=1;k<=z;k++){
                       
                         if(A[i][j-k]=='#'||(j-k)<0){
                           break;
                        }
                        else {
                          if(A[i][j-k]=='@'){
                             B[m]++;
                          }
                        }
                     
                 }
                
                 }
             }
         }
    
    int max=B[m];
    int g,h;
    g=x-1;
    h=y-1;
    for(;m>0;m--){
        //printf("%d\n",m);
        if(B[m]>=max){
            max=B[m];
            g=(m-1)/y;
            h=(m-1)-(g*y);
        }
    
    }
    if(max==0){
         for(int i=x-1;i>=0;i--){
                for(int j=y-1;j>=0;j--){
                        if(A[i][j]=='.'){
                            printf("%d %d\n",i,j);
                            printf("%d\n",max);
                            goto here;
                         }
                }
        }
    }

    
 
    printf("%d %d\n",g,h);
    printf("%d\n",max);
    
    here:
    
    
    
    return 0;
}
