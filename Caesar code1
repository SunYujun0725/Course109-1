//
//  main.c
//  HW W13-3
//
//  Created by 孫渝鈞 on 2020/12/5.
//  Copyright © 2020 孫渝鈞. All rights reserved.
//
#include<stdio.h>
#include<string.h>
#include<ctype.h>
int main()
{
    int n;
    scanf("%d",&n);      //輸入要移的位置數
    char str1[10];        //如果是用fgets的話enter鍵也會讀入鍵所以要另外設個字串來存這個enter鍵
    fgets(str1,10,stdin);
    char str[100001];       //輸入字串 加\0是100001
    fgets (str, 100001, stdin);
    int m = 0;
    while (*(str + m) != '\0')  //找字串長度
    {
      m++;
    }
if(n>=0){
  for(int i=0;i<m;i++){
        if(islower(str[i])){
            if(islower(str[i]+n)){
                printf("%c",str[i]+n);}
            else{
                printf("%c",str[i]+n-26);
            }
            
        }
        else if(isupper(str[i])){
            if(isupper(str[i]+n)){
                printf("%c",str[i]+n);
            }
            else{
                printf("%c",str[i]+n-26);
            }
        }
        else{
            printf("%c",str[i]);
        }
    }
}
else{
    for(int i=0;i<m;i++){
        if(islower(str[i])){
            if(islower(str[i]+n)){
                printf("%c",str[i]+n);}
            else{
                printf("%c",str[i]+n+26);
            }
            
        }
        else if(isupper(str[i])){
            if(isupper(str[i]+n)){
                printf("%c",str[i]+n);
            }
            else{
                printf("%c",str[i]+n+26);
            }
        }
        else{
            printf("%c",str[i]);
        }
    }
    
}
    
    
    
    return 0;
}
