//
//  main.c
//  HW W7-2
//
//  Created by 孫渝鈞 on 2020/10/22.
//  Copyright © 2020 孫渝鈞. All rights reserved.
//
#include<stdio.h>
int main()
{
    int num[200000];
    int N;
    int i, j, tmp;
    scanf("%d",&N);
    for(i=0;i<N;i=i+1)
    {
     scanf("%d",&num[i]);
    }

    
    for( i=0 ; i<N ; i=i+1 )
    {
        for( j=i+1 ; j<N ; j=j+1 )
        {
            if( num[i] > num[j] )
            {
               
                tmp = num[i];
                num[i] = num[j];
                num[j] = tmp;
            }
        }
    }

   
    for( i=0 ; i<N ; i=i+1 )
    {
        printf("%d",num[i]);
        printf(" ");
    }
    printf("\n");
    

    return 0;
}
