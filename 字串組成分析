//
//  main.c
//  HW W13-2
//
//  Created by 孫渝鈞 on 2020/12/4.
//  Copyright © 2020 孫渝鈞. All rights reserved.
//
#include <stdio.h>
#include <string.h>
int main()
{
    char inp[100000];
    int cnt[128];

    int i;

    scanf("%s", inp);

    for(i=0;i<76;i++)
        cnt[i] = 0;

    for(i=0; inp[i] ; i++)
    {
        cnt[inp[i]-'0']++;
    }

   

    for(i=0;i<76;i++){
        if(cnt[i]!=0){
                printf("%c %d\n", '0'+i, cnt[i]);
        }
    
    }
    
    return 0;
}
