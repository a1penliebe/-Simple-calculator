# include <iostream>
using namespace std;

int main() {

  char c;
  float num1, num2;

  cout << "Enter operator: +, -, *, /: ";
  cin >> c;

  cout << "Enter numbers: \n";
  cout<<"number 1 = ";
  cin >> num1;
  cout<< "number 2 = ";
  cin>>num2;

  switch(c) {

    case '+':
      cout << num1 << " + " << num2 << " = " << num1 + num2;
      break;

    

    case '*':
      cout << num1 << " * " << num2 << " = " << num1 * num2;
      break;

    case '/':
      cout << num1 << " / " << num2 << " = " << num1 / num2;
      break;
  
    case '-':
      cout << num1 << " - " << num2 << " = " << num1 - num2;
      break;

    default:
     
      cout << "Error! operator is not correct";
      break;
  }

  return 0;
}

