//
//  main.c
//  HW W11-1
//
//  Created by 孫渝鈞 on 2020/11/12.
//  Copyright © 2020 孫渝鈞. All rights reserved.
//
/*  probID: 11-1-Explore  */
#define MAX_N 50
#define MAX_M 50

int n, m;
char grid_map[MAX_N][MAX_M];
int visited[MAX_N][MAX_M];

void Explore( int x, int y );
int dirs[4][2] = {
    {1,0}, {-1,0}, {0,-1}, {0,1}
};
void Explore (int x,int y){
    
        visited[x][y]=1;
    
    for(int i=0;i<=3;i++){// 考慮 (x,y) 周圍上、下、左、右四個方向
     if( grid_map[x+dirs[i][0]] [y+dirs[i][1]]=='.'&&visited[x+dirs[i][0]][y+dirs[i][1]]==0 ){
         if(x+dirs[i][0]>=0 && x+dirs[i][0]<n && y+dirs[i][1]>=0 && y+dirs[i][1]<m){
                       Explore( x+dirs[i][0], y+dirs[i][1] );
               }
           }
    }
}
/*#include <stdio.h>

extern int n,m;
extern char grid_map[50][50];
extern int visited[50][50];

void Explore(int,int);

int main()
{
    scanf("%d%d", &n, &m);
    for(int i=0; i<n; i++)
    {
        char tmp[100];
        scanf("%s", tmp);
        
        for(int j=0; j<m; j++)
        {
            grid_map[i][j] = tmp[j];
            visited[i][j] = 0;
        }
    }
        
    int x, y;
    scanf("%d%d", &x, &y);
    
    Explore(x,y);
    
    for(int i=0; i<n; i++)
    {
        for(int j=0; j<m; j++)
            printf("%s%d", j?" ":"", visited[i][j]);
        printf("\n");
    }
    
    return 0;
}
*/
