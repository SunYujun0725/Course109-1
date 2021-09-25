//
//  main.c
//  HW W8-3
//
//  Created by 孫渝鈞 on 2020/10/25.
//  Copyright © 2020 孫渝鈞. All rights reserved.
//

#include <stdio.h>

int main()
{
    int n;
    scanf("%d",&n);
    int a[n];
    for(int i=0;i<n;i++){
        scanf("%d",&a[i]);
    }
    int left;
    int right;
    scanf("%d %d",&left,&right);
    int x;
    scanf("%d",&x);
   for(int i=0;i<left;i++){
       printf("%d",a[i]);
       printf(" ");
   }
   for(int i=left;i<=right;i++){
       if(a[i]<a[x]){
           printf("%d",a[i]);
           printf(" ");
       }
   }

   printf("%d",a[x]);
   printf(" ");
   
   for(int i=left;i<=right;i++){
       if(a[i]>=a[x]){
           if(i!=x){
               printf("%d",a[i]);
               printf(" ");
               
           }
       }
   }
   
   for(int i=right+1;i<n;i++){
       printf("%d",a[i]);
       printf(" ");
       }
    return 0;
}
  
