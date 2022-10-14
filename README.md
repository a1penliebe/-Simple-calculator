# include <iostream>
using namespace std;

int main() {

  char c;
  float num1, num2;

  
  cout << "Enter numbers: \n";
  cout<<"number 1 = ";
  cin >> num1;
  cout<< "number 2 = ";
  cin>>num2;
   cout << "Enter operator: +, -, *, /: ";
  cin >> c;

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
     
      cout << " Error !operator is not currently added";
      break;
  }

  return 0;
}

