# Print-even-numbers
method 03


#include<iostream>
using namespace std;
int main()
{
int i,n;
cout<<"\n Enter the starting value:";
cin>>i;
cout<<"\n Enter the Ending value:";
cin>>n;
start:
if(i%2==0)
{
cout<<"\n"<<i;
}
i++;
if(i<=n)
{
goto start;
}
return 0;
}
