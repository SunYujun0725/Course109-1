//
//  main.c
//  HW W12-2
//
//  Created by 孫渝鈞 on 2020/11/14.
//  Copyright © 2020 孫渝鈞. All rights reserved.
//

/* qsort example */
#include <stdio.h>      /* printf */
#include <stdlib.h>     /* qsort */

int compare (const void * a, const void * b)
{
  return ( *(int*)a - *(int*)b );
}

int main ()
{
  int n;
  scanf("%d",&n);
    int A[n];
    for(int i=0;i<n;i++){
        scanf("%d",&A[i]);//scanf("%d",&A+i);
    }
  qsort (A, n, sizeof(int), compare);
  for (int i=0; i<n; i++)
     printf ("%d ",A[i]);//printf("%d ",*(A+i));
  return 0;
}
