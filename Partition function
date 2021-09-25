//
//  main.c
//  HW W10-1
//
//  Created by 孫渝鈞 on 2020/11/7.
//  Copyright © 2020 孫渝鈞. All rights reserved.
//

/*  probID: 10-1-Partition  */
/* #include <stdio.h>

int Partition_by_key(int[],int,int,int);

int A[200000], n;
int left, right, key;

int main()
{
    scanf("%d", &n);
    for(int i=0; i<n; i++)
        scanf("%d", &A[i]);
    scanf("%d %d %d", &left, &right, &key);
    
    key = Partition_by_key(A, left, right, key);
    for(int i=0;i<n;i++)
    printf("%d ", A[i]);
    printf("\n%d\n", key);
    
    return 0;
}*/
int  Partition_by_key( int A[], int left, int right, int key)
{
    int B[200000];
    int i=left;
    int j=0;
    int count=0;
    int k2=left;
    for(int i=left;i<=right;i++){
        if(A[i]<A[key]){
            B[j]=A[i];
            j++;
            count++;
            k2++;
        }
    }
    B[j]=A[key];
    j++;
    count++;
    int k=A[key];
    for(int i=left;i<=right;i++){
        if(A[i]>=k){
            if(i!=key){
            B[j]=A[i];
            j++;
            count++;
            }
                
            
        }
    }
    for(int j=0;j<count;j++){
        A[i]=B[j];
        i++;
    }
    
    
  
    key=k2;
    return key;
    

}
