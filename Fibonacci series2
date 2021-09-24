//
//  main.c
//  HW W4-5-2
//
//  Created by 孫渝鈞 on 2020/10/2.
//  Copyright © 2020 孫渝鈞. All rights reserved.
//

#include <stdio.h>

#define FIBARRAYSIZE 100
int main()
{
    int n;
    scanf("%d",&n);
    
    int fab [FIBARRAYSIZE];
    fab[0]=0;
    fab[1]=1;
    for (int i=2;i<n;i++){
        fab[i]=fab[i-1]+fab[i-2];
    }
    if(n>1){
    printf("%d\n",fab[n-1]+fab[n-2]);
    }
    else{
        printf("%d\n",fab[n]);
    }
    
  
    return 0;
}
