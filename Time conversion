//
//  main.c
//  HW W2-2
//
//  Created by 孫渝鈞 on 2020/9/17.
//  Copyright © 2020 孫渝鈞. All rights reserved.
//
#include<stdio.h>
int main()
{
    int x,a,b,c,d;

    scanf("%d",&x);
    
    if(x<60)
    {
       a=0;
       b=0;
       c=x;
        
    }
    else if (x<3600)
    {
        a=0;
        b=(x-(x%60))/60;
        c=x%60;
    }
    else
    {
        d=(x-(x%60))/60;
        a=(d-(d%60))/60;
        b=((x-(x%60))/60)%60;
        c=x%60;
        
        
    }
    printf("%d\n",a);
    printf("%d\n",b);
    printf("%d\n",c);
    
    return 0; 
    
    
    
}
