# 50-Days-Of-Solving-C-
It's MahaCodeDays.


### Day 01: March 04, 2022 

**Today's Progress**: 

//Write a C++ Program to Find Sum and Average of three numbers. Here’s simple C++ Program to Find Sum and Average of three numbers in C++ Programming Language.

Solution : 
#include<iostream>
using namespace std;

int main()
{
    float a,b,c,sum,avg;
    cout<<"Enter 1st number :: ";
    cin>>a;
    cout<<"\nEnter 2nd number :: ";
    cin>>b;
    cout<<"\nEnter 3rd number :: ";
    cin>>c;

    sum=a+b+c;

    avg=sum/3;

    cout<<"\nThe SUM of 3 Numbers [ "<<a<<" + "<<b<<" + "<<c<<" ] = "<<sum<<"\n";
    cout<<"\nThe AVERAGE of 3 Numbers [ "<<a<<", "<<b<<", "<<c<<" ] = "<<avg<<"\n";

    return 0;
} 
  
  
