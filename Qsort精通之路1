//
//  main.c
//  HW W14-4
//
//  Created by 孫渝鈞 on 2020/12/10.
//  Copyright © 2020 孫渝鈞. All rights reserved.
//
#include <stdio.h>
#include <stdlib.h>
#include <string.h>
int num_of_lines=0;
char str[100000][103];
char **t;
const char **na,**nb;
int compare(const void *a, const void *b)
{
    na = (const char **)a;
    nb = (const char **)b;
     return strcmp(*na,*nb) ;
}
int main()
{
     while ((fgets(str[num_of_lines],103,stdin)) != NULL)
        ++num_of_lines;
   
    t= ( char** )malloc( num_of_lines * sizeof( char* ) );
    for (int i=0;i< num_of_lines;i++)
    {
        t[i] = ( char* )malloc( 103 * sizeof( char ) );
    }
    for(int x=0;x<num_of_lines;x++){
      strcpy(t[x], str[x]);
    }
    qsort(t,num_of_lines,sizeof(char *),compare);
    
    for(int x=0;x<num_of_lines;x++)
        printf("%s",t[x]);
    putchar('\n');

    return 0;
}
