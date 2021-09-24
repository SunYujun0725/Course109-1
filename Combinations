//
//  main.c
//  HW W4-4-2
//
//  Created by 孫渝鈞 on 2020/10/2.
//  Copyright © 2020 孫渝鈞. All rights reserved.
//

#include<stdio.h>
int a,b;
int f(int a,int b){
    if(a==b){
        return 1;
    }
    if(b==0){
        return 1;
    }
    return f(a-1,b-1)+f(a-1,b);
}

int main()
{   scanf ("%d %d",&a,&b);
    printf("%d\n",f(a,b));
    return 0;
}

