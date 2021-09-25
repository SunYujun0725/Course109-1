//
//  main.cpp
//  HW W13-3-2
//
//  Created by 孫渝鈞 on 2020/12/5.
//  Copyright © 2020 孫渝鈞. All rights reserved.
//

#include<iostream>
#include<string>
using namespace std;
int main(){
    
    string input;
    int n,intput;
    while(cin>>n){
        if(n>=0){
        while(cin>>input){
            
            for(int i=0;i<input.length();i++){
                
            
            
                if(input[i]>='A'&&input[i]<='Z'){
                    intput = (int)(input[i]+n);
                    if(intput>90){
                        intput = (intput-26);
                    }
                    cout << (char)intput;
                }else if(input[i]>='a'&&input[i]<='z'){
                    intput = (int)input[i]+n;
                    if(intput>122){
                        intput = (intput-26);
                }
                    cout << (char)intput;
                }else{
                    cout<<input[i];
                }
            }
            
            cout <<" ";
    
        }
        }
        else{
            while(cin>>input){
                    
                    for(int i=0;i<input.length();i++){
                        
                    
                    
                        if(input[i]>='A'&&input[i]<='Z'){
                            intput = (int)(input[i]+n);
                            if(intput>90){
                                intput = (intput-26);
                            }
                            cout << (char)intput;
                        }else if(input[i]>='a'&&input[i]<='z'){
                            intput = (int)input[i]+n;
                            if(intput>122){
                                intput = (intput-26);
                        }
                            cout << (char)intput;
                        }else{
                            cout<<input[i];
                        }
                    }
                    
                    cout <<" ";
            
                }
        }
    }
}
