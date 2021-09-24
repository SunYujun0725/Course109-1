//
//  main.c
//  HW W5-2
//
//  Created by 孫渝鈞 on 2020/10/2.
//  Copyright © 2020 孫渝鈞. All rights reserved.
//

#include <stdio.h>

int main()
{
    int n,i,k,a;
    scanf("%d",&n);
    a = 0;
    for(i=2;i<=n;i++){
      int is_prime = 1;
        if(i==2){
             if(n%i==0){
                 while(n%i==0){
                 n=n/2;
                 a++;
                 }
            printf("%d",i);
            printf(" ");
            printf("%d\n",a);
        }
    }
        
    a=0;
    for( k = 2; k < i; k++ ){
          if( i%k == 0 ){
              is_prime = 0;
              break;
          }
          if( is_prime==1 ){ 
              if(n%i==0){
                  while(n%i==0){
                     n=n/i;
                     a++;
                  }
                  
                  printf("%d",i);
                  printf(" ");
                  printf("%d\n",a);
                  break;
            }
          }
      }
}
    
    return 0;
}
