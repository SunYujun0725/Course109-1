//
//  main.c
//  HW W6-4-2
//
//  Created by 孫渝鈞 on 2020/10/10.
//  Copyright © 2020 孫渝鈞. All rights reserved.
//
#include<stdio.h>
#include<math.h>

int main(){
    int t;
    scanf("%d",&t);
    int x[t],y[t];
    for(int i=0;i<t;i++){
        scanf("%d",&x[i]);
        scanf("%d",&y[i]);
    }
    long max=0;
    for(int j=0;j<t;j++){
        for(int m=j+1;m<t;m++){
        int X=x[m]-x[j];
        int Y=y[m]-y[j];
        long s=pow(X,2)+pow(Y,2);
            if(s>max){
                max=s;
            }
        }
    }
      
     int root=sqrt(max)+0.5;
      
      printf("%d\n",root);
   
     return 0;
}

