//
//  main.c
//  HW W5-1
//
//  Created by 孫渝鈞 on 2020/9/30.
//  Copyright © 2020 孫渝鈞. All rights reserved.
//

#include<stdio.h>
#define MAX 1000

int main()
{
   int i=0,n,a[MAX],b,c;
    scanf("%d",&n);
    while (n>0)
    {
       a[i] = n%2;
       i = i+1;
        n = n/2;
    }
    
    if (i<=4){
        for (;i>0;i--)
     {
         printf("%d",a[i-1]);
            
     }
    }
    else{
        b=i%4;
        for(c=0;c<b;c++){
            printf("%d",a[i-1]);
            i--;
        }
        printf(" ");
        
        for(;i>0;i-=4){
            printf("%d",a[i-1]);
            printf("%d",a[i-2]);
            printf("%d",a[i-3]);
            printf("%d",a[i-4]);
            printf(" ");
            
        }
        
    }
    


   return 0;

}
