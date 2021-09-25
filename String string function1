//
//  main.c
//  HW W15-1
//
//  Created by 孫渝鈞 on 2020/12/16.
//  Copyright © 2020 孫渝鈞. All rights reserved.
//
/*  probID: 15-1-StringString  */
#include <string.h>
char *StringString( const char *str, const char *substr ){
    return strstr(str,substr);
}
           
/*#include <stdio.h>
#include <string.h>

char *StringString(const char*, const char*);

int main()
{
    char str[10000], substr[10000];
    char *ptr;
    
    fgets(str, 10000, stdin);
    fgets(substr, 10000, stdin);
    
    if(substr[strlen(substr) - 1] == '\n')
        substr[strlen(substr) - 1] = '\0';
    
    ptr = StringString(str, substr);
    
    while(ptr)
    {
        printf("%s", ptr);
        
        ptr += strlen(substr);
        ptr = StringString(ptr, substr);
    }
    
    return 0;
}*/
