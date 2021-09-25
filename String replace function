//
//  main.c
//  HW W14-3
//
//  Created by 孫渝鈞 on 2020/12/10.
//  Copyright © 2020 孫渝鈞. All rights reserved.
//
/*  probID: 14-3-StringReplace  */
#include <stdlib.h>
#include <string.h>
char *StringReplace(char *str,const char *t,const char *r) {
    char *result;
    char *ins;
    char *tmp;
    long len_rep;
    long len_with;
    long len_front;
    int count;
    if (!str || !t)
        return NULL;
    len_rep = strlen(t);
    if (len_rep == 0)
        return NULL;
    if (!r)
        r = "";
    len_with = strlen(r);
    ins = str;
    for (count = 0; tmp = strstr(ins,t); ++count){
        ins = tmp + len_rep;
    }
    tmp = result = malloc(strlen(str) + (len_with - len_rep) * count + 1);

    if (!result)
        return NULL;

   
    while (count--) {
        ins = strstr(str, t);
        len_front = ins - str;
        tmp = strncpy(tmp, str, len_front) + len_front;
        tmp = strcpy(tmp, r) + len_with;
        str += len_front + len_rep;
    }
    strcpy(tmp, str);
    return result;
}
/*#include <stdio.h>
#include <string.h>

char *StringReplace(char*,const char*,const char*);

char *NextSlash( char *ptr )
{
    while( *ptr != '/' )
        ptr++;
    return ptr;
}

char *ExtractToken( char *target, char *ptr )
{
    char *nxt_ptr = NextSlash(++ptr);
    long len = nxt_ptr - ptr;
 
    strncpy(target, ptr, len);
    *(target+len) = 0;
    
    return nxt_ptr;
}

int main()
{
    char buf[20000];
    char s[10000],t[100],r[100];
    
    while(fgets(buf,20000,stdin))
    {
        char *ptr = NextSlash(buf);
            
        ptr = ExtractToken(s,ptr);
        ptr = ExtractToken(t,ptr);
        ExtractToken(r,ptr);
        
        printf("%s\n",StringReplace(s,t,r));
    }
    
    return 0;
}*/

