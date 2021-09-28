# Exercises
C++ 
/// Odd or Even ///

#include <iostream>
using namespace std;

int main () {
  int n;

  cout << "Enter an integer: ";
  cin >> n;

  if ( n % 2 == 0)
   cout << n << "is even.";
  else
   cout << n << " is odd.";
   
   return 0;
}

/// Number Checker ///

#include <iostream>
using namespace std;

int main () {
    
  int num;
  cout << "Enter the number to checked : ";
  cin >> num;
  if(num >=0){
  cout << num << " is a positive number.";
}
  else 
    cout << num << " is a negative number.";
  return 0;
}

/// Profit or Loss ///

#include <iostream>
using namespace std;

int main (){

  int cp,sp,profit,loss;
  cout <<"enter cost price:" <<endl;
  cin >> cp;
  cout <<"enter selling price:" <<endl;
  cin >> sp;
 if (sp>cp) 
 {
   profit = sp - cp;
   cout << "profit" << profit <<endl;
 }
 else if(cp>sp)
 {
 loss = cp - sp;
 cout << " loss of " << loss << endl;
 }
 else
 {
   cout << " no profit no loss."; 
 }
 return 0;
}

/// Name that Shape ///

#include <iostream>
using namespace std;

int main (){

  int sides;
  cout << "Enter the sides of shape" <<endl;
  cin>>sides;

  if(sides == 1)
  {
    cout << "The shape does not exist" <<endl;
  }
  if(sides == 2)
  { 
    cout << "The shape does not exist" <<endl;
  }
  if(sides == 3)
  {
      cout << "The shape is triangle" <<endl;
  }
  if(sides == 4)
  {
      cout << "The shape is square" <<endl;
  }  
  if(sides == 5)
  {
      cout << "The shape is pentagon" <<endl; 
  }
  if(sides == 6)
  {
      cout << "The shape is hexagon" <<endl; 
  }
  if(sides == 7)
  {
      cout << "The shape is heptagon" <<endl; 
  }
  if(sides == 8)
  {
      cout << "The shape is octagon" <<endl; 
  }
  if(sides == 9)
  {
      cout << "The shape is nonagon" <<endl; 
  }  
  if(sides == 10)
  {
      cout << "The shape is decagon" <<endl; 
  }
  if(sides > 10)
  {
      cout << "error" <<endl; 
  }
  return 0;
}
