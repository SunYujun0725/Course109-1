//
//  main.c
//  HW W9-2-2
//
//  Created by 孫渝鈞 on 2020/11/7.
//  Copyright © 2020 孫渝鈞. All rights reserved.
//

#include <stdio.h>

int main()
{   int x,y;
    scanf("%d %d",&x,&y);

    char A[x][y];
    for(int i=0;i<x;i++){
        for(int j=0;j<y;j++){
            scanf(" %c",&A[i][j]);
        }
    }
    int count=0;
    for(int i=0;i<x;i++){
        for(int j=0;j<y;j++){
              int a=i+1;
              int b=i-1;
              int c=j+1;
              int d=j-1;
            if(A[i][j]=='+'){
                if(A[a][j]=='@'&&a<x){count++; A[a][j]='.';}
                if(A[b][j]=='@'&&b>=0){count++; A[b][j]='.'; }
                if(A[i][c]=='@'&&c<y){count++; A[i][c]='.'; }
                if(A[i][d]=='@'&&d>=0){count++; A[i][d]='.'; }
            }
        }
    }
    printf("%d",count);
    printf("\n");

    return 0;
}
