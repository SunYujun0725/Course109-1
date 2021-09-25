//
//  main.c
//  HW W8-1
//
//  Created by 孫渝鈞 on 2020/10/24.
//  Copyright © 2020 孫渝鈞. All rights reserved.
//

#include <stdio.h>

int main()
{   int n;
    scanf("%d",&n);
    int a[n];
    for(int i=0;i<n;i++){
        scanf("%d",&a[i]);
    }
    int b;
    scanf("%d",&b);
    int c[b];
    for(int j=0;j<b;j++){
        scanf("%d",&c[j]);
    }
    int x;
    int i;
    for(int j=0;j<b;j++){
        i=0;
        x=1;
        for(;i<n;i++){
            if(c[j]==a[i]){
                printf("Found!\n");
                x=0;
                break;
            }
        }
        if(x==1){
            printf("not found\n");
        }
    }
   
    return 0;
}
