#include <iostream>
using namespace std;

int main()
{
    int num;
    
    cout<<"Input Any Positive Integers:";
    cin>>num;
    
    while(true)
    {
        if (num%2!=0)
        {
            num = (num*3)+1;
            cout<< "Given Value is:"<<num<<endl;
            
            if(num==1)
            {
                break;
                }
            }
        
       else if(num%2==0)
        {
            num = num / 2;
            cout<<"Current Given Value is:"<<num<<endl;
            
            if(num==1)
            {
                break;
                }
            }
        }

       }
