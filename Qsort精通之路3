//
//  main.c
//  HW W14-4-3
//
//  Created by 孫渝鈞 on 2020/12/22.
//  Copyright © 2020 孫渝鈞. All rights reserved.
//
#include <stdio.h>
#include <stdlib.h>
#include <string.h>

#define MAX 103
//submitted
int compare(const void *a, const void *b);

int main()
{

    int n=0,j;

    char str[100][MAX];
    while ((fgets(str[n],MAX,stdin)) != NULL)
        ++n;

    int x;

//    printf("Original: ");
//    for(x=0;x<n;x++)
//        printf("%s ",str[x]);
//    putchar('\n');


    char **tab;
    tab = ( char** )malloc( n * sizeof( char* ) );

    for ( size_t i = 0; i < n; i++ )
    {
        tab[i] = ( char* )malloc( MAX * sizeof( char ) );
    }

    for(x=0;x<n;x++){
      strcpy(tab[x], str[x]);
    }

    /* quicksort the list */
    //printf("%d\n\n",sizeof(char *));
    qsort(tab,n,sizeof(char *),compare);

    /* print sorted strings */
    //printf("  Sorted: ");
    for(x=0;x<n;x++)
        printf("%s",tab[x]);
    putchar('\n');

    return(0);
}

int compare(const void *a, const void *b)
{
    const char **pa,**pb;

    pa = (const char **)a;
    pb = (const char **)b;
    return( strcmp(*pa,*pb) );
}
