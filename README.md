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

    cout<<"\nThe SUM of 3 Numbers = " <<sum<< endl;
    cout<<"\nThe AVERAGE of 3 Numbers = " <<avg<< endl;

    return 0;
} 
    
    
//Write a C++ Program to Find Quotient and Remainder of 2 numbers. Here’s simple C++ Program to Find Quotient and Remainder of 2 numbers in C++ Programming Language. 
    
Solution: 
#include <iostream>
using namespace std;

int main()
{
    int divisor, dividend, quotient, remainder;

    cout << "Enter dividend";
    cin >> dividend;

    cout << "Enter divisor";
    cin >> divisor;

    quotient = dividend / divisor;
    remainder = dividend % divisor;

    cout << "Quotient = " << quotient  <<endl;
    cout << "Remainder = " << remainder<<endl;

    return 0;
} 
    

### Day 02: March 05, 2022 
    
**Today's Progress**:
    
//Strings in C++ ||

STL-Strings [NOTES: https://drive.google.com/file/d/1EMlDaf0O_mXlTTB5kuj6VhbyQpLqJ8we/view]

To use strings in a program, you need to include a header called string.
For example:

Declaring a string

It declares a string of value “Kanad”

It declares a string of size 10.

It declares a string of size 5 with all characters ‘N’.

It declares a copy of the string str.

Taking Input
We use cin to input the string.

cin >> str;

Using getline() function: To input the string with space we use getline() function
instead of cin.

Input: a peaceful buddy
Output: Kanad is a peaceful buddy

Throwing Output
We use cout to throw output to the terminal.
cout << str;

Different functions of string
1. append(): Inserts additional characters at the end of the string (can also be
done using ‘+’ or ‘+=’ operator). Its time complexity is O(N) where N is the
size of the new string.

Output: family

2. assign(): Assigns new string by replacing the previous value (can also be
done using ‘=’ operator).

Output: Rishabh

3. at(): Returns the character at a particular position (can also be done using ‘[
]’ operator). Its time complexity is O(1).

Output: c
c

4. begin(): Returns an iterator pointing to the first character. Its time
complexity is O(1).
5. clear(): Erases all the contents of the string and assign an empty string (“”)
of length zero. Its time complexity is O(1).

No Output, as string is empty.

6. compare(): Compares the value of the string with the string passed in the
parameter and returns an integer accordingly. Its time complexity is O(N +
M) where N is the size of the first string and M is the size of the second
string.

Output: 1513239 - basically a value greater than 0 denoting s2 is greater

than s1.

Output: 0 - as both string are equal.

Output: -1513239 - basically a value less than 0 denoting s2 is less than s1.
7. c_str(): Convert the string into C-style string (null terminated string) and
returns the pointer to the C-style string. Its time complexity is O(1).
8. empty(): Returns a boolean value, true if the string is empty and false if the
string is not empty. Its time complexity is O(1).

Output: given string is empty

9. end(): Returns an iterator pointing to a position which is next to the last
character. Its time complexity is O(1).
10.erase(): Deletes a substring of the string. Its time complexity is O(N) where
N is the size of the new string.

Output: ninpoop

11.find(): Searches the string and returns the first occurrence of the parameter
in the string. Its time complexity is O(N) where N is the size of the string.

Output: 3

12.insert(): Inserts additional characters into the string at a particular position.
Its time complexity is O(N) where N is the size of the new string.

Output: nilolncompoop

13.length(): Returns the length of the string. Its time complexity is O(1).

Output: 10

14.resize(): Resize the string to the new length which can be less than or
greater than the current length. Its time complexity is O(N) where N is the
size of the new string.

Output: nincom

15.size(): Returns the length of the string. Its time complexity is O(1).

Output: 10

16.substr(): Returns a string which is the copy of the substring. Its time
complexity is O(N) where N is the size of the substring. For example:

Output: comp

17.stoi(): Returns the strings converted to int datatype.

Output: 788

Note:
1. To convert an integer to a string, we use to_string() function. Example

Output: 7682.

2. Sorting a string: To sort a string, we need to include a header file known as algorithm in our code like this

Then we can use sort() function that is present in above header file on our string.
Sort() function takes 2 arguments viz. iterator to start of the string and iterator to
end of the string.

Output: acdfkmnsxz

KEEP CODING AND IMPROVE YOUR CODING SKILLS !!
  
  
