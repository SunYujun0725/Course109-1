//
//  main.c
//  HW W14-2-2
//
//  Created by 孫渝鈞 on 2020/12/10.
//  Copyright © 2020 孫渝鈞. All rights reserved.
//
/*  probID: 14-2-NextVowel  */
char *NextVowel( char *s ){

    while(*s!=0){
    if(*s==97||*s==101||*s==105||*s==111||*s==117||*s==65||*s==69||*s==73||*s==79||*s==85){
        return s;
    }
    else{
        s++;
    }
    }
    if(*s==0){
        return 0;
    }

}
/*#include <stdio.h>

char *NextVowel(char*);

int main()
{
    char s[100];

    while(scanf("%99s",s)==1)
    {
        char *current_ptr = NextVowel(s);
        while( current_ptr )
        {
            putchar(*current_ptr);
            current_ptr = NextVowel(++current_ptr);
        }
        putchar('\n');
    }

    return 0;
}*/
