//
//  main.c
//  HW W15-1-2
//
//  Created by 孫渝鈞 on 2020/12/17.
//  Copyright © 2020 孫渝鈞. All rights reserved.
//
/*  probID: 15-1-StringString  */
char *StringString( const char *str, const char *substr ){
    int i=0;
    int v=0;
    int count=0;
    int count2=0;
   
    while(*(substr+i)!='\0'){
        count++;
        i++;
    }
    i=0;
    int check=0;
    int j=i;
    
    while(*(str+i)!='\0'){
        j=i;
        while(*(str+j)==*(substr+v)){
            count2++;
            j++;
            v++;
            if(count2==count){
                check=1;
                return str+j-count;
            }
        }
        count2=0;
        i++;
        v=0;
    }
  
    return 0;
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
