//
//  main.c
//  HW W10-2
//
//  Created by 孫渝鈞 on 2020/11/9.
//  Copyright © 2020 孫渝鈞. All rights reserved.
//
/*  probID: 10-2-QuickSort  */
#include <stdlib.h>
#define MAX 10
#define SWAP(x,y) {int t; t = x; x = y; y = t;}

int partition(int[], int, int);
void rescurive_quick_sort(int[], int, int);
void quick_sort(int[],int);
int partition(int A[], int left, int right) {
    int i = left - 1;
    int j;
    for(j = left; j < right; j++) {
        if(A[j] <= A[right]) {
            i++;
            SWAP(A[i], A[j]);
        }
    }

    SWAP(A[i+1], A[right]);
    return i+1;
}

void recursive_quick_sort(int A[], int left, int right) {
    if(left < right) {
        int q = partition(A, left, right);
        recursive_quick_sort(A, left, q-1);
        recursive_quick_sort(A, q+1, right);
    }
}
void quick_sort( int A[], int n ){
    recursive_quick_sort( A, 0, n-1 );
    
}
/*#include <stdio.h>

void quick_sort(int[],int);

int A[200000], n;

int main()
{
    scanf("%d", &n);
    for(int i=0; i<n; i++)
        scanf("%d", &A[i]);
    
    quick_sort(A, n);
    
    for(int i=0;i<n;i++)
        printf("%d ", A[i]);
    printf("\n");
    
    return 0;
}*/

