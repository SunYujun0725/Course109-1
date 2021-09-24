//
//  main.c
//  HW W3-3
//
//  Created by 孫渝鈞 on 2020/9/18.
//  Copyright © 2020 孫渝鈞. All rights reserved.
//

#include <stdio.h>
#include <math.h>
int main()

{
    double a,b,c,d,e,f,g,h,i,j;
    scanf("%lf %lf",&a,&b);
    scanf("%lf %lf",&c,&d);
    scanf("%lf %lf",&e,&f);
    
    g=(d-b)/(c-a);
    
    h=(f-b)/(e-a);
    
    i=c-a;
    j=e-a;
    if(fabs(i-j)<1e-6)
    {
        printf("Collinear\n");
    }
    else {
        if (fabs(g-h) < 1e-6 )
        {
           printf("Collinear\n");
         }
        else
        {
          printf("General Position\n");
         }
    
    }
    return 0;
}
