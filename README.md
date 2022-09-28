# pattern-question-3
   1
  232
 34543
4567654

#include <iostream>

using namespace std;

int main()
{
 int n,i,j,a;
 cin>>n;
 
 for( i=1;i<=n;i++){
   
 for(j=1;j<=i-1;j++){
     int a=2*i-2;
cout<<a;
a=a-1;
 }
     cout<<endl;
 }

    return 0;
}
