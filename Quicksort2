//
//  main.c
//  HW W10-2-2
//
//  Created by 孫渝鈞 on 2020/11/22.
//  Copyright © 2020 孫渝鈞. All rights reserved.
//
/*  probID: 10-2-QuickSort  */
#include <stdio.h>
#include <stdlib.h>
#include <time.h>
#define max 200000


void quick_sort( int A[], int n );
void recursive_quick_sort(int A[], int, int);
int Partition_by_key( int A[], int left, int right, int key );


int Partition_by_key( int a[], int left, int right, int key )
{

    int counter=0,ct_l=0,ct_r=0;
    int b[max],c[max];
    int temp=a[key];

    for(int i=left; i<=right; i++)
    {
        if(a[i]<a[key])
            b[ct_l++]=a[i];
        else
        {
            if(i != key)
                c[ct_r++]=a[i];
        }
    }


    counter=left;

    for(int i=0 && ct_l>0; i<ct_l; i++)
    {
        a[counter]=b[i];
        counter+=1;
    }

    a[counter]=temp;
    counter++;

    for(int i=0 && ct_r>0; i<ct_r; i++)
    {
        a[counter]=c[i];
        counter+=1;
    }


    return ct_l+left;



}


void quick_sort( int A[], int n )
{

    recursive_quick_sort( A, 0, n-1 );
}
void recursive_quick_sort( int A[], int left, int right )
{
    int key;
    srand(time(NULL));

    if(left>right)
        return;
    key= rand()%(right-left+1)+left;

    key=Partition_by_key(A,left,right,key);;

    recursive_quick_sort(A, left,key-1);
    recursive_quick_sort(A,key+1,right);
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
