//
//  main.c
//  HW W7-1
//
//  Created by 孫渝鈞 on 2020/10/22.
//  Copyright © 2020 孫渝鈞. All rights reserved.
//

/*  probID: 7-1-MinPos  */
int MinPos(int A[],int left,int right)//傳參數的值(傳入值)
{
    int j=left;
    int k=j+1;
    for(;right>left;){
        
        if(A[j]<A[k]){
            k=k+1;
            right=right-1;
        }
        else{
            j=k;
            k=j+1;
            right=right-1;
        }
    }
    return j;
}

#include <stdio.h>
int MinPos(int[],int,int);

int A[1000], n;

int main()
{
    scanf("%d", &n);
    for(int i=0; i<n; i++)
        scanf("%d", &A[i]);
        
    int t;
    int left, right;
    
    scanf("%d", &t);
    while(t--)
    {
        scanf("%d %d", &left, &right);
        printf("%d\n", MinPos(A, left, right));
    }
    
    return 0;
}

