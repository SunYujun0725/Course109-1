//
//  main.cpp
//  HW W15-3-2
//
//  Created by 孫渝鈞 on 2020/12/18.
//  Copyright © 2020 孫渝鈞. All rights reserved.
//
#include<iostream>
#include<string>
#include<cstdlib>
using namespace std;
int main() {
    string s;
    while(cin>>s) {

        if(s.length()==1){
            if(s[0]>='A'&&s[0]<='Z'){
                cout<<'"'<<s[0]<<'"'<<endl;
            }else if(s[0]>='a'&&s[0]<='z'){
                cout<<'"'<<s[0]<<'"'<<endl;
            }else{
                cout<<s[0]<<endl;
            }
        }else{
            if(s[0]>='A'&&s[0]<='Z'){
                cout<<'"'<<s[0];
            }else if(s[0]>='a'&&s[0]<='z'){
                cout<<'"'<<s[0];
            }else if((s[0]>'Z'&&s[0]<'a')||s[0]<'A'||s[0]>'z'){
                cout<<s[0]<<endl;
            }
            for(int i=1;i<s.length();i++){
                if((s[i]>='0'&&s[i]<='9')||s[i]==','||s[i]=='.'||s[i]=='?'||s[i]=='\''||s[i]==':'||s[i]=='+'||s[i]=='-'||s[i]=='*'||s[i]=='/'||s[i]=='('||s[i]==')'){
                    if((s[i-1]>='A'&&s[i-1]<='Z')||(s[i-1]>='a'&&s[i-1]<='z')){
                        cout<<'"'<<endl<<s[i]<<endl;
                    }else{
                        cout<<s[i]<<endl;
                    }
                }else{
                    if((s[i-1]>='0'&&s[i-1]<='9')||s[i-1]==','||s[i-1]=='.'||s[i-1]=='?'||s[i-1]=='\''||s[i-1]==':'||s[i-1]=='+'||s[i-1]=='-'||s[i-1]=='*'||s[i-1]=='/'||s[i-1]=='('||s[i-1]==')'){
                        cout<<'"'<<s[i];
                    }else{
                        cout<<s[i];
                    }
                }
                if(i==s.length()-1){
                    if((s[i]>='0'&&s[i]<='9')||s[i]==','||s[i]=='.'||s[i]=='?'||s[i]=='\''||s[i]==':'||s[i]=='+'||s[i]=='-'||s[i]=='*'||s[i]=='/'||s[i]=='('||s[i]==')'){
                        continue;
                    }else{
                        cout<<'"'<<endl;
                    }
                }
                
                
            }
            
            
            
        }
        
            
    }
    
}
