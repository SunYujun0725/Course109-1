//
//  main.c
//  HW W14-4-2
//
//  Created by 孫渝鈞 on 2020/12/13.
//  Copyright © 2020 孫渝鈞. All rights reserved.
//
#include<stdio.h>
#include<string.h>
#include<stdlib.h>

int a,b;
int cmp(const void*a, const void*b)
{
    return strcmp(a,b);
}
int strcmp(const char *a,const char*b);

int main()
{
    int n=0;
    char str[100][103];

    while(fgets(str[n],103,stdin)!=NULL)
        n++;

    qsort(str,n,sizeof(char)*103,cmp);
    printf("\n");
    for(int i=0;i<n;i++)
        printf("%s",str[i]);
    return 0;
}
