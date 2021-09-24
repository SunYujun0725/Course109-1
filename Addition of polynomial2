//
//  main.c
//  HW W6-2
//
//  Created by 孫渝鈞 on 2020/10/8.
//  Copyright © 2020 孫渝鈞. All rights reserved.
//

#include <stdio.h>


int main()
{
      int m,n;
      scanf("%d",&m);
      int a[m];
      for(int i=m;i>=0;i--){
          scanf("%d",&a[i]);
      }
      scanf("%d",&n);
      int b[n];
      for(int i=n;i>=0;i--){
        scanf("%d",&b[i]);
    }
     if(m>n){
         for(int i=m;i>n;i--){
             printf("%d",a[i]);
             printf(" ");
        }
         for(int i=n;i>=0;i--){
             printf("%d",a[i]+b[i]);
             printf(" ");
        }
     }else{
         for(int i=n;i>m;i--){
             printf("%d",b[i]);
             printf(" ");
        }
         for(int i=m;i>=0;i--){
             printf("%d",a[i]+b[i]);
             printf(" ");
        }
     }

    return 0;
}



