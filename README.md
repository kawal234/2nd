# 2nd

#include<iostream>
using namespace std;

//First program of Operators Chapter Day-2
int main(){

    int num1 = 10;
    int num2 = 20;

    bool exp1 = true;
    bool exp2 = false;

    //Operators
    // cout<<num1+num2<<endl;
    // cout<<num1-num2<<endl;
    // cout<<num1*num2<<endl;
    // cout<<num1/num2<<endl;

    // Relational operators
    // cout<<(num1==num2)<<endl;// false
    // cout<<(num1!=num2)<<endl;// true
    // cout<<(num1>num2)<<endl;// false

    // Logical Operators
    // cout<<(exp1&&exp2)<<endl;// false
    // cout<<(exp1||exp2)<<endl;// true
    // cout<<(!exp1)<<endl;// false

    // Assignment Operator
    // cout<<(num1+=1)<<endl;
    // cout<<(num2-=10)<<endl;

    cout<<(num1<<1)<<endl;
    cout<<(num2>>2)<<endl;

    //size of
    // condition?exp1:exp2
    //{.} is for classes and {->} is for pointers
    // we can a float num to a int num also known as casting operator
    // {&} this is used to give addresss to a value
    // {*} this is used as to point the address of the variable


    cout<< sizeof(num1)<<endl;
    return 0;
}
