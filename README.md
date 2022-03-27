// c++ program to calculate the sum of two numbers
#include<iostream>
using namespace std;
int main()
{
   // declare two integers 
   // intialize the sum with zero because it may have garbage value
   int a,b,sum=0;
   // get the value from user use cin
   cout<<"enter the first number :";
   cin>>a;
   cout<<"enter the second number :";
   cin>>b;
   //store sum of a and b to sum 
   sum=a+b;
   //display the sum
   cout<<"the sum of given numbers is :"<<sum;
   
    return 0;
}
