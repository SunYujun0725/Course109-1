//
//  main.c
//  HW W10-3-2
//
//  Created by 孫渝鈞 on 2020/11/12.
//  Copyright © 2020 孫渝鈞. All rights reserved.
//
#include<stdio.h>
int main()
{
    char a[100][101];//假设这里的地图大小不超过20*20
    int i,j,n,m,k;
    //读入n和m，n表示有多少行字符，m表示每行有多少列
    scanf("%d %d",&m,&n);
    for(i=0; i<m; i++){
        for(j=0;j<n;j++){
            scanf(" %c",&a[i][j]);}}
    scanf("%d",&k);
    //读入n行字符

   int ans=0;
    int bestx=0,besty=0;

    for(int i=0;i<m;i++){
        for(int j=0;j<n;j++){
            if(a[i][j]!='.')
                continue;
            int facksum=0;
            for(int c=1;c<k+1;c++){
                //加1，每炸多一格多加一//
            if(a[i+c][j]=='#'||(i+c)>100||(i+c)<0)
            break;
                //如果炸多過n格就停//
            if(a[i+c][j]=='@')
                facksum++;
                //炸到怪temp就加
            }
                for(int c=1;c<k+1;c++){
                if(a[i-c][j]=='#'||(i+c)>100||(i+c)<0)
                break;
                if(a[i-c][j]=='@')
                    facksum++;
                }
                    for(int c=1;c<k+1;c++){
                    if(a[i][j+c]=='#'||(i+c)>100||(j+c)>100)
                    break;
                    if(a[i][j+c]=='@')
                        facksum++;
                                }
                        for(int c=1;c<k+1;c++){
                        if(a[i][j-c]=='#'||(i+c)>100)
                        break;
                        if(a[i][j-c]=='@')
                            facksum++;
                        }
            if(facksum>=ans){
                ans=facksum;
                bestx=i;
                besty=j;
            }
            /*else if(facksum==ans){
                ans=facksum;
                bestx=i;
                besty=j;
            }*/
        }
    }

    printf("%d %d\n%d",bestx,besty,ans);
    return 0;
}
