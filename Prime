//
//  main.c
//  HW W4-2
//
//  Created by 孫渝鈞 on 2020/9/23.
//  Copyright © 2020 孫渝鈞. All rights reserved.
//

#include <stdio.h>

int main()
{
  int a,i;

  scanf("%d", &a);

  int is_prime = 1;

  for( i = 2; i < a; i++ )
  {
      if( a % i == 0 )
      {
          is_prime = 0;
          break;
      }
  }

  if( is_prime==1 )
      printf("Prime\n");
  else
      printf("Composite\n");
    return 0;
}
