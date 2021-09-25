//
//  main.c
//  HW W14-2
//
//  Created by 孫渝鈞 on 2020/12/9.
//  Copyright © 2020 孫渝鈞. All rights reserved.
//
/*  probID: 14-2-NextVowel  */
#include <string.h>
#include <stdio.h>
char *NextVowel(char*s){
    char *ptr = strtok(s, " ");

    while( ptr )
    {
        int n = 0;
        while (*(ptr + n) != '\0')
        {
            n++;
            
        }
        for(int i=0;i<n;i++){
            if(ptr[i]=='A'||ptr[i]=='E'||ptr[i]=='I'||ptr[i]=='O'||ptr[i]=='U'||ptr[i]=='a'||ptr[i]=='e'||ptr[i]=='i'||ptr[i]=='o'||ptr[i]=='u'){
                printf("%c",ptr[i]);
            }
        }
        ptr = strtok(NULL, " ");
    }
    return 0;
    
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
