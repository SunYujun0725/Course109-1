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
    int a;   //第一個多項式的最高次數
    int d;   //第一個多項式的各項係數
    scanf("%d",&a);
    int i;
    i=0;
    int b [a]; //第一個多項式陣列
    for(i=0;i<=a;i++){
        scanf("%d",&d);
        b[i]=d;
    }
    int e;//第二個多項式的最高次數
    int g;  //第一個多項式的各項係數
    scanf("%d",&e);
    int f;
    f=0;
    int c [e];
    for(f=0;f<=e;f++){
        scanf("%d",&g);
        c[f]=g;
    }
    if (a<e){
        i=0; //歸０
        f=0; //歸０
        int h;
        h=e%a; //取餘數 代表前面有幾個數不用相加
        for(f=0;f<h;f++){
            printf("%d",c[f]);
            printf(" ");
        }
       
        for(f=h;f<=e;f++){  //剩下的用迴圈相加
            while(i<=a){
                printf("%d",b[i]+c[f]);
                i++;
                break;
            }
            if(f!=e){
                printf(" ");
            }
           
            
        }
        
    }

    else{  //反過來如果第二個比較長
        i=0;
        f=0;
        int h;
        h=a%e;
         for(i=0;i<h;i++){
                   printf("%d",b[i]);
                   printf(" ");
               }
       
        for(i=h;i<=a;i++){
            while(f<=e){
                printf("%d",b[i]+c[f]);
                f++;
                break;
            }
            if(i!=a){
                printf(" ");
            }
            
            
        }
       
    }
    

    
    return 0;
}
