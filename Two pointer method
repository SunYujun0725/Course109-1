//
//  main.c
//  HW W8-4
//
//  Created by 孫渝鈞 on 2020/10/26.
//  Copyright © 2020 孫渝鈞. All rights reserved.
//
/*  probID: 8-4-Two-Pointer-Method  */
int merged[20000000];
void merge( int a, int b, int A[], int B[], int merged[] )
{
    int j=0,k=0;
    int i=0;
    while(i<a+b){
        if(A[k]<B[j]){
            merged[i]=A[k];
            k++;
        }
        else{
            merged[i]=B[j];
            j++;
        }
        if(k==a){
            i++;
            while(j<b){
                merged[i]=B[j];
                i++;
                j++;
            }
            
        }
        if(j==b){
            i++;
            while(k<a){
                merged[i]=A[k];
                i++;
                k++;
            }
        }
        i++;
    }
}
/*#include <stdio.h>

int A[10000000], B[10000000];
int merged[20000000];

void merge(int, int, int[], int[], int[]);

int main()
{
    int a, b, i;
    scanf("%d %d", &a, &b);
    
    for(i=0; i<a; i++)
        scanf("%d", &A[i]);
    
    for(i=0; i<b; i++)
        scanf("%d", &B[i]);
    
    merge(a, b, A, B, merged);
    
    for(i=0; i<a+b; i++)
    {
        printf("%d ", merged[i]);
    }
    printf("\n");
    
    return 0;
}*/

