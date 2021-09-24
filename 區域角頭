//
//  main.c
//  HW W6-3
//
//  Created by 孫渝鈞 on 2020/10/10.
//  Copyright © 2020 孫渝鈞. All rights reserved.
//

#include <stdio.h>

int main()
{
    int x,y;
    scanf("%d %d",&x,&y);
    int a [x][y];
  
    for(int i=0;i<x;i++){
        for(int j=0;j<y;j++){
            scanf("%d",&a[i][j]);
        }
    }
  
    for(int i=0;i<x;i++){
        
        if(i==0){
        for(int j=0;j<y;j++){
            if(j==0){
                if( a[i][j]>a[i+1][j] && a[i][j]>a[i][j+1] ){
                    printf("%d\n",a[i][j]);
                  }
            }
            else if(j==y-1){
                if(a[i][j]>a[i+1][j]&&a[i][j]>a[i][j-1]){
                    printf("%d\n",a[i][j]);
                    }
            }
            else{
                if(a[i][j]>a[i+1][j]&&a[i][j]>a[i][j-1]&&a[i][j]>a[i][j+1]){
                    printf("%d\n",a[i][j]);
                }
            }
         }
        }
        else if(i==x-1){
              for(int j=0;j<y;j++){
               if(j==0){
                  if( a[i][j]>a[i-1][j] && a[i][j]>a[i][j+1] ){
                      printf("%d\n",a[i][j]);
                    }
              }
              else if(j==y-1){
                  if(a[i][j]>a[i-1][j]&&a[i][j]>a[i][j-1]){
                      printf("%d\n",a[i][j]);
                      }
              }
              else{
                  if(a[i][j]>a[i-1][j]&&a[i][j]>a[i][j-1]&&a[i][j]>a[i][j+1]){
                      printf("%d\n",a[i][j]);
                  }
              }
           }
           
      }
        else{
            for(int j=0;j<y;j++){
                    if(j==0){
                       if( a[i][j]>a[i-1][j] && a[i][j]>a[i][j+1] && a[i][j]>a[i+1][j] ){
                           printf("%d\n",a[i][j]);
                         }
                   }
                   else if(j==y-1){
                       if(a[i][j]>a[i-1][j]&&a[i][j]>a[i][j-1] && a[i][j]>a[i+1][j]){
                           printf("%d\n",a[i][j]);
                           }
                   }
                   else{
                       if(a[i][j]>a[i-1][j]&&a[i][j]>a[i][j-1]&&a[i][j]>a[i][j+1] &&a[i][j]>a[i+1][j]){
                           printf("%d\n",a[i][j]);
                       }
                   }
                }
            }
    }
        

   
 return 0;
        
 }
