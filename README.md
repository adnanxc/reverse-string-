# reverse-string-

#include <iostream>
using namespace std;

string reverser (string a){
   string rev;
   int length = a.length();
   
   for(int i=length-1; i>=0; i--){
        rev+=a[i];
   }
   return rev;
}




int main(){
    string s;
    cout << "Enter your string: ";
    getline(cin,s);

    cout << "Reverse string: " << reverser(s);
}
