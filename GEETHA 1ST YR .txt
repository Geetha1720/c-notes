HELLO WORLD

//first c++ program CODE:

\#include<iostream>

using namespace std;





int main()

{

&nbsp;   cout<<"hello world";

&nbsp;   return 0;

}



-----------------------------------------------------------------------------------------------------------

TO ENTER UR REG NO

\#include<iostream>

using namespace std;





int main()

{

&nbsp;   int a=18;

&nbsp;   cout<<"enter your reg no:"<<a;

&nbsp;   return 0;

}

-----------------------------------------------------------------------------------------------------------



TO ENTER REG NO WITH CIN

\#include<iostream>

using namespace std;





int main()

{

&nbsp;   int a;

&nbsp;   cout<<"enter your reg no:";

&nbsp;   cin >>a;

&nbsp;   cout <<" your reg no is:"<<a;

&nbsp;   return 0;

}

-----------------------------------------------------------------------------------------------------------



REG NO URS AND UR FRNDS A AND B

\#include<iostream>

using namespace std;





int main()

{

&nbsp;   int a;

&nbsp;   int b;

&nbsp;   cout<<"enter your reg no:nezuko";

&nbsp;   cin >>a;

&nbsp;   cout<<"enter your frnds reg no";

&nbsp;   cin>>b;

&nbsp;   cout <<" your reg no is:"<<a;

&nbsp;   cout<<"your frnd reg no is:"<<b;

&nbsp;   return 0;

}



-----------------------------------------------------------------------------------------------------------

REG NO UR AND UR FRNDS A AND B ENDL

// to enter register no

\#include<iostream>

using namespace std;





int main()

{

&nbsp;   int a;

&nbsp;   int b;

&nbsp;   cout<<"enter your reg no:nezuko.";

&nbsp;   cin >>a;

&nbsp;   cout<<"enter your frnds reg no";

&nbsp;   cin>>b;

&nbsp;   cout <<" your reg no is:"<<a<<endl;

&nbsp;   cout<<"your frnd reg no is:"<<b;

&nbsp;   return 0;

}

-----------------------------------------------------------------------------------------------------------



1.int which mean integer: which store integer values(whole no.)i.e 1,2,3,4,5

2.variables :in c++ are used to store data and manipulated through program

3.float:used to store decimal values:10.4,10.6

4.double:(double precision) which mean accurate answer i.e 10.777 etc..

5.char: used to store single character i.e A,b etc...

6.STRING: string is a sequence of characters ,usually used to represent text such as words or sentences.

eg:"hello world"   'hi'

----------------------------------------------------------------------------------------


TO SHOW DIFFERENT DATA TYPES:
// DATA TYPES IN C++
#include<iostream>
using namespace std;


int main()
{
    //integer data type used to store whole no.
    int A=18;  
    
    //float data type used to store decimal no.
    float B=0.17;  
    
    //double data (double precision) which mean accurate answer
    double C=10.628181;
    
    // char data type used to store single character
    char D='G';
    
    //string is a sequence of characters ,usually used to
    //represent text such as words or sentences
    string E="NEZUKO";
    
    
    //To show the data:
    cout<<"integer :"<<A<<endl;
    cout<<"float :"<<B<<endl;
    cout<<"double :"<<C<<endl;
    cout<<"char :"<<D<<endl;
    cout<<"string :"<<E<<endl;
    
    return 0;
}

------------------------------------------------------------------------------------------------------------

operators in c++
1.
Operators in C++
Operators in C++ are symbols used to perform operations on variables and values. They are essential for building logic and performing computations in programs. Here's a categorized overview:

1. Arithmetic Operators
Used for basic mathematical operations:

+ : Addition
- : Subtraction
* : Multiplication
/ : Division
% : Modulus (remainder)

Example:
Cppint a = 10, b = 3;
int sum = a + b;  // 13
int mod = a % b;  // 1


2. Relational (Comparison) Operators
Used to compare two values:

== : Equal to
!= : Not equal to
>  : Greater than
<  : Less than
>= : Greater than or equal to
<= : Less than or equal to

Example:
Cppif (a > b) {
    cout << "a is greater than b";
}


3. Logical Operators
Used to combine conditional statements:

&& : Logical AND
|| : Logical OR
!  : Logical NOT

Example:
Cppif (a > 0 && b > 0) {
    cout << "Both are positive numbers";
}


4. Bitwise Operators
Operate at the bit level:

&  : AND
|  : OR
^  : XOR
~  : Complement
<< : Left shift
>> : Right shift

Example:
Cppint x = 5;  // Binary: 0101
int y = 3;  // Binary: 0011
int result = x & y;  // Binary: 0001 (1 in decimal)


5. Assignment Operators
Used to assign values:

=  : Assign
+= : Add and assign
-= : Subtract and assign
*= : Multiply and assign
/= : Divide and assign
%= : Modulus and assign

Example:
Cppint c = 10;
c += 5;  // c = c + 5; Result: 15


6. Increment and Decrement Operators
Used to increase or decrease a value by 1:

++ : Increment
-- : Decrement

Example:
Cppint d = 5;
d++;  // d becomes 6
--d;  // d becomes 5


7. Miscellaneous Operators

sizeof : Returns the size of a variable
?: : Ternary operator (conditional)
& : Address-of operator
* : Pointer dereference
-> : Member access through pointer
. : Member access
, : Comma operator

Example:
Cppint size = sizeof(int);  // Returns size of int in bytes
int max = (a > b) ? a : b;  // Ternary operator


8. Type Casting Operators
Used to convert data types:

static_cast
dynamic_cast
const_cast
reinterpret_cast

Example:
Cppfloat f = 3.14;
int i = static_cast<int>(f);  // Converts float to int


Operator Precedence
Operators have a specific precedence that determines the order of evaluation in expressions. For example, multiplication (*) has higher precedence than addition (+).

C++ operators are versatile and form the backbone of programming logic. Understanding their usage and precedence is crucial for writing efficient code!

------------------------------------------------------------------------------------------------------------

ARTHAMATICAL OPERATION:
//operators in c++ :
#include<iostream>
using namespace std;

int main()
{
    int a=10,b=20;
    cout <<"addition:"<<a+b<<endl;
    cout <<"subraction:"<<a-b<<endl;
    cout <<"division:"<<a/b<<endl;
    cout <<"multipication:"<<a*b<<endl;
    
    return 0;
}


RELATIONAL OPERATION:
int main()
{
    int a=10,b=20;
    cout <<"equals to:"<<(a=b)<<endl;
    cout <<"greater:"<<(a>b)<<endl;
    cout <<"lesser:"<<(a<b)<<endl;
    cout <<"greater than or equals to:"<<(a>=b)<<endl;
    cout <<"lesser than or equals to:"<<(a<=b)<<endl;
    
    return 0;
    
}


LOGICAL OPERATION:
#include<iostream>
using namespace std;

int main()
{
    int a=10,b=20;
    cout <<"logical AND:"<<(a<0 && b>0)<<endl;
    cout <<"logical OR:"<<(a>0||b<0)<<endl;
    cout <<"logical NOT:"<<(a>0)<<endl;
   
  return 0;

}

-------------------------------------------------------------------------------------------------------------------------------------------------
USER INFORMATION:

#include<iostream>
using namespace std;
int main()
{
    string name;
    int age;
    float height;
    double weight;
    char blood_group;
    char grade;
    
    // collect user information
    cout <<"enter your name:";
    cin>>name;
    
    cout<<"enter the age:";
    cin>>age;
    
    cout<<"enter your height:";
    cin>>height;

    cout<<"enter your weight:";
    cin>>weight;
    
    cout<<"enter the blood_group:";
    cin>>blood_group;

    cout<<"enter the grade:";
    cin>>grade;
    
    //display the collected information
    cout<< "\n--- user information ---\n";
    cout<< "name :"<<name << endl;
    cout<< "age :" <<age<< "years"<<endl;
    cout<< "height :"<<height<<"m"<<endl;
    cout<< "weight :"<<weight<<"kg"<<endl;
    cout<< "blood_group :"<<blood_group<<"+VE"<<endl;
    cout<< "grade :" <<grade<<endl;
    
    return 0;
    
 }
--------------------------------------------------------------------------------------------------------------

//BITWISE OPERATION:
#include<iostream>
using namespace std;

int main()
{
    int a=10,b=20;
    cout <<"BITWISE AND:"<<(a<1 && b>0)<<endl;
    cout <<"bitwse OR:"<<(a>0|b<0)<<endl;
    cout <<"logical NOT:"<<(a>0)<<endl;
   
  return 0;

}
------------------------------------------------------------------------------------------------------------BINARY NUBERS:
0.
2.
3.
4.
5.
6.
7.
8.
9.
10.
11.
12.
13.
14.
15.
------------------------------------------------------------------------------------------------------------
#include<iostream>
using namespace std;
int main()
{
    int a=10;
    if (a>18)
  {
    cout<<"A IS GREATER THAN 18";
  }
    cout<<"A IS LESS THAN 18";        

    return 0;
}


#include<iostream>
using namespace std;
int main()
{
    int a=10;
    if (a>18)
  {
    cout<<"A IS GREATER THAN 18";
  }
   else{
    cout<<"A IS LESS THAN 18";        
   } 
    return 0;
}


#include<iostream>
using namespace std;
int main()
{
    int a=10;
    if (a>18)
  {
    cout<<a<<"A IS GREATER THAN 18";
  }
   else{
    cout<<a<<"A IS LESS THAN 18";        
   } 
    return 0;
}



#include<iostream>
using namespace std;
int main()
{
    int age;
    cout<<"enter your age :";
    cin>> age;
    if (age>=18)
  {
    cout<<"HE/SHE IS ELIGIBLE TO VOTE";
  }
   else{
    cout<<"NoT ELIGIBLE"; 
    cout<<18-age<<" more year to vote";       
   } 
    return 0;
}


#include<iostream>
using namespace std;
int main()
{
    int a;
    cout<<"ENTER A NUMBER :";
    cin>>a;
    if (a%2==0)
  {
    cout<<" IS EVEN!";
  }
   else{
    cout<<a<<" IS ODD!";        
   } 
    return 0;
}


#include<iostream>
using namespace std;
int main()
{
    int age;
    cout<<"ENTER A age :";
    cin>>age;
    if (age>=18)
  {
    cout<<" your eligible to vote daa";
  }
   else{
    cout<<" your still a minor"<<endl<<18-age<<" more years to vote";        
   
       
   } 
    return 0;
}


#include<iostream>
using namespace std;
int main()
{
    int i=1;
    while(i <=18)
    {
        cout<<i<<endl;
        i++;
    }
   return 0;
}
