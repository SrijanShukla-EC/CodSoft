#include<iostream>
int main(){
char op;
double num1;
double num2;
double result;
std::cout<<" ***** This is a simple Calculator ***** \n";
std::cout<<"_________________________________________ \n";
std::cout<<"Enter the first number: ";
std::cin>>num1;
std::cout<<"Enterthe second number: ";
std::cin>>num2;
std::cout<<"Enter the Operand (+,-,*,/): ";
std::cin>>op;
switch(op){
    case'+':
              result= num1 + num2;
              std::cout<<" The solution is: "<<result<<'\n';
              break;
    case '-':
        	    result = num1 - num2;
        	    std::cout<<"The result : "<<result<<'\n';
        	    break;
    case '*':
        	    result = num1 * num2;
        	    std::cout<<"The result : "<<result<<'\n';
        	    break;
    case '/':
        	    result = num1 / num2;
        	    std::cout<<"The result : "<<result<<'\n';
        	    break;
    deafaul:
        	    std::cout<<"Enter either +, -, * or /.";
                break;      
}
return 0;
}
