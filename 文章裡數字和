//
//  main.c
//  HW W15-4
//
//  Created by 孫渝鈞 on 2020/12/17.
//  Copyright © 2020 孫渝鈞. All rights reserved.
//

#include <stdio.h>
#include <ctype.h>
#include <stdbool.h>
#include <math.h>
int main()
{
    char str=getchar();
    int ans=0;
    char str2[1000000];
    int i=0;
    int n=0;
    while(str!=EOF){    //ex:345fvnoinfiv
       
        if(isdigit(str)){        //str=3
            i=0;
            n=0;
            str2[i]=getchar();   //str2[0]=4
            if(isdigit(str2[i])){  //如果下個字元也是數字的話
                 
                while(isdigit(str2[i])){    //迴圈判斷總共有幾個迴數字連再一起
                    i++;                //i=2
                    n++;   //計算有幾個數字 //n=2
                    str2[i]=getchar();  //str2[1]=5
                }
              
                int i=-1; //i要從-1進入迴圈因為這樣再跑第二次str[i]才會是str[0]
                int k=n;  //k=2
                for(;i<n;i++){
                  while(k>=0){   //i=-1,k=2進入
                      if(k==n){
                          ans=ans+((int)(str-48))*(pow(10,k)); //+300
                          k--;   //k=1
                          break;  //跳出裡面那層迴圈裡面那層迴圈再再重新進入以i=0,k=1重新進入
                      }
                      else if(k>0){   //i=0,k=1
                          ans=ans+((int)(str2[i]-48))*(pow(10,k)); //+40
                          k--;  //k=0
                          break;  //跳出裡面那層迴圈裡面那層迴圈再再重新進入以i=1,k=0重新進入
                      }
                      else if(k==0){  //i=1,k=0
                          ans=ans+((int)(str2[i]-48));  //+5
                          k--;
                          break;  //跳出迴圈i=2=n不會進入迴圈了
                      }
                   }
                }
            }
            else{        //如果下個字元不是數字的話
                ans=ans+(int)(str-48);    //直接加
                
            }
            
             }
            str=getchar();
         }
        printf("%d\n",ans);
         return 0;
}


