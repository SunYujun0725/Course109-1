//
//  main.c
//  HW W15-3
//
//  Created by 孫渝鈞 on 2020/12/17.
//  Copyright © 2020 孫渝鈞. All rights reserved.
//
#include <stdio.h>
#include <string.h>
#include <ctype.h>
//#include <stdbool.h>
char _my_buffer;
int _is_my_buffer_filled = 0;
void read_identifier();
void read_number();
void read_punc();
void read_operator();
char peek_next_char(){
    if(_is_my_buffer_filled==0){
        _my_buffer = getchar();
        _is_my_buffer_filled=1;
    }
    return _my_buffer;
    
}
void my_getchar(){
    if(_is_my_buffer_filled==1){
        _is_my_buffer_filled=0;
       // putchar(_my_buffer);
    }
   
}
void read_identifier()
{
    
    printf("\"");
    char _my_buffer3;
    char _my_buffer2=getchar();
    if(isupper(_my_buffer2)||islower(_my_buffer2)||_my_buffer2=='_'||isdigit(_my_buffer2)){
         putchar(_my_buffer);
        while(isupper(_my_buffer2)||islower(_my_buffer2)||_my_buffer2=='_'||isdigit(_my_buffer2)){
        _my_buffer3=_my_buffer2;
        _my_buffer2=getchar();
        putchar(_my_buffer3);
     }
       
  
        
    }
    
    else{putchar(_my_buffer);}
        printf("\"");
 
    printf("\n");
    if(_my_buffer2==44||_my_buffer2==46||_my_buffer2==63||_my_buffer2==39||_my_buffer2==':'){
        _my_buffer=_my_buffer2;
        read_punc();
    }
    else if(_my_buffer2=='+'||_my_buffer2=='-'||_my_buffer2=='*'||_my_buffer2=='/'||_my_buffer2=='('||_my_buffer2==')'){
         _my_buffer=_my_buffer2;
         read_operator();
    }
}
void read_number()
{
   
    char _my_buffer3;
    char _my_buffer2=getchar();
    if(isdigit(_my_buffer2)){
         putchar(_my_buffer);
        while(isdigit(_my_buffer2))
        {
            _my_buffer3=_my_buffer2;
            _my_buffer2=getchar();
            putchar(_my_buffer3);
        }
      
    }
    else{
       putchar(_my_buffer);
        
    }
    
    printf("\n");
    if(isupper(_my_buffer2)||islower(_my_buffer2)||_my_buffer2=='_'){
         _my_buffer=_my_buffer2;
        read_identifier();
    }
    else if(_my_buffer2==44||_my_buffer2==46||_my_buffer2==63||_my_buffer2==39||_my_buffer2==':'){
        _my_buffer=_my_buffer2;
        read_punc();
    }
    else if(_my_buffer2=='+'||_my_buffer2=='-'||_my_buffer2=='*'||_my_buffer2=='/'||_my_buffer2=='('||_my_buffer2==')'){
       _my_buffer=_my_buffer2;
        read_operator();
    }
}
void read_punc()
{
    putchar(_my_buffer);
    printf("\n");
}
void read_operator()
{
    putchar(_my_buffer);
    printf("\n");
}
int main()
{
    _my_buffer=peek_next_char();
    while(_my_buffer!=EOF)
    {
        
        if(_my_buffer==32||_my_buffer==9||_my_buffer==10||_my_buffer==13)
              my_getchar();
        else if(isupper(_my_buffer)||islower(_my_buffer)||_my_buffer=='_'){
            
            read_identifier();
        }
        else if(isdigit(_my_buffer)){
           
            read_number();
        }
        else if(_my_buffer==44||_my_buffer==46||_my_buffer==63||_my_buffer==39||_my_buffer==':'){
           
            read_punc();
        }
        else if(_my_buffer=='+'||_my_buffer=='-'||_my_buffer=='*'||_my_buffer=='/'||_my_buffer=='('||_my_buffer==')'){
          
            read_operator();
        }
        
        _my_buffer= getchar();
    }
    return 0;
}
