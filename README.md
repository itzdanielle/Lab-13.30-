# Lab-13.30-
#include <iostream>
using namespace std;

int main() {
  int num1;
  int num2;
  double product;
  int y;
  int n;
  char answer;

  cout << "Enter first number:" << endl;
  cin >> num1;
  cout << "Enter second number:" << endl;
  cin >> num2;
 product = num1 * num2;
 cout << "The product is " << product << endl << endl;

 cout << "Multiply more numbers? (y/n):" << endl;
 cin >> answer; 
  
 while (answer == 'y') { 
  
  cout << "Enter first number:" << endl;
  cin >> num1;
  cout << "Enter second number:" << endl;
  cin >> num2;
 product = num1 * num2;
 cout << "The product is " << product << endl << endl;
   
 cout << "Multiply more numbers? (y/n):" << endl;
 cin >> answer;
 }
  
  cout << "Goodbye." << endl;

}
