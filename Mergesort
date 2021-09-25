//
//  main.c
//  HW W12-1
//
//  Created by 孫渝鈞 on 2020/11/13.
//  Copyright © 2020 孫渝鈞. All rights reserved.
//
/*  probID: 12-1-MergeSort  */

void MergeSortedArrays(  int C[], int c, int D[], int d, int merged[])
{
    int j=0,k=0;
    int i=0;
    while(i<c+d){
        if(C[k]<D[j]){
            merged[i]=C[k];
            k++;
        }
        else{
            merged[i]=D[j];
            
            j++;
        }
        if(k==c){
            i++;
            while(j<d){
                merged[i]=D[j];
                i++;
                j++;
            }
            
        }
        if(j==d){
            i++;
            while(k<c){
                merged[i]=C[k];
                i++;
                k++;
            }
        }
        i++;
    }
    

}
void recursive_merge_sort( int A[], int left, int right, int temp[] )
{
    if(left>=right){
        return;
    }
    int mid=(left+right)/2;
    recursive_merge_sort( A, left, mid, temp );
    recursive_merge_sort( A, mid+1, right, temp );
    MergeSortedArrays( A+left, mid-left+1,A+mid+1, right-mid, temp );
    for(int i=left,j=0;i<right+1;i++){
        A[i]=temp[j];
        j++;
    }
    return;
}
 
void merge_sort( int A[], int n ){
    int temp[n];
     recursive_merge_sort( A, 0, n-1, temp );
}
/*#include <stdio.h>

void merge_sort(int[],int);

int A[200000], n;

int main()
{
    scanf("%d", &n);
    for(int i=0; i<n; i++)
        scanf("%d", &A[i]);
    
    merge_sort(A, n);
    
    for(int i=0;i<n;i++)
        printf("%d ", A[i]);
    printf("\n");
    
    return 0;
}*/

