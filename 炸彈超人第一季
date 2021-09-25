//
//  main.c
//  HW W9-2
//
//  Created by 孫渝鈞 on 2020/11/7.
//  Copyright © 2020 孫渝鈞. All rights reserved.
//
#include<stdio.h>



int main()

{

    char a[101][101];

    int i,j,n,m,ans=0;

    scanf("%d %d",&n,&m);


            for(i=0;i<n;i++){


                scanf("%s",a[i]);
            }


    for(i=0;i<n;i++){
    for(j=0;j<m;j++){

                if(a[i][j]=='+'&&a[i+1][j]=='@'&&(i+1)<n+1)
                {

                ans=ans+1;
                    a[i+1][j]='.';
                }

                if(a[i][j]=='+'&&a[i-1][j]=='@'&&(i-1)>=0)
                {

                 ans=ans+1;
                    a[i-1][j]='.';
                }
        if(a[i][j]=='+'&&a[i][j-1]=='@'&&(j-1)>=0)
       {

           ans=ans+1;
           a[i][j-1]='.';
       }

                 if(a[i][j]=='+'&&a[i][j+1]=='@'&&(j+1)<m+1)
                {

                    ans=ans+1;
                    a[i][j+1]='.';
                }


                }
      }


    printf("%d",ans);
    printf("\n");
    return 0;
    
}


