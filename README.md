# Exercises
C++ 

# Exercises2_
C++
/// Mark my words ///

#include <iostream>
using namespace std;

int main (){

int percentage;
cout <<"Enter the percentage:" <<endl;
cin>>percentage;

if(percentage >= 70)
{ cout <<"The letter grade is A" <<endl;
}
if ((percentage > 60) && (percentage < 69))
{ cout <<"The letter grade is B" << endl;
}
if ((percentage > 50) && (percentage < 59))
{ cout <<"The letter grade is C" << endl;
}
if ((percentage > 40) && (percentage < 49))
{ cout <<"The letter grade is D" << endl;
}
if (percentage < 40)
{ cout <<"The letter grade is F" << endl;
}
return 0;
}


/// Starting a Band ///

#include <iostream>
using namespace std;

int main() {
	bool musicalfriend = true;  bool nonmusicalfriend = false;
// This is the nested if-else statement that governs the decisions
if (musicalfriend) {
if (nonmusicalfriend) {
cout << "Do you want to be the guitarist of the band?" <<endl;
} else {
cout << "Do you want to be the guitarist of the band?" << endl;
}
} else {
cout << "okay, thank you :D" << endl;
}

int answer;
cout << "Write your answer: 99 - Yes or 00 - No 55 - I want to be the drummer of the band:" <<endl;
cin>>answer;

if(answer == 99)
{ 
    cout <<"Welcome to our band! You are now qualified <333" <<endl;
}
if(answer == 00)	
{
    cout <<"okay, thank you for your time!:D" <<endl;
}
if(answer == 55)
    cout <<"Sure! You are qualified as the drummer!!! Welcome, cool XD" <<endl;
return 0;
}


/// Killing Time ///

#include <iostream>
using namespace std;

int main (){

int minutes;
cout <<"How many minutes will you wait for your friend? She said __ minutes: Enter the minutes" <<endl;
cin>> minutes;

if(minutes >= 15 )
{ cout <<"Oh I will wait too long so I have decided to buy some things. :)" <<endl; 
cout <<"Cashier: Hi madam! your total bill is 170 dhs. (I pay my 200 dhs money)"  <<endl; 
cout <<"Uhmm I still have 30 dhs change"  <<endl; 
cout <<"Imma buy coffee and go for a walk"  <<endl; 
}
if (minutes < 15)
{ cout <<"Oh She will come sooner so I have decided to sit in the food zone and wait :)" << endl;
}

return 0;
}


/// Earthquake ///

#include <iostream>
using namespace std;
int main()
{
	int Magnitude;
	cout <<"Enter the Magnitude of the Earthquake:";
	cin >> Magnitude;
	

if(Magnitude < 2.0)    
{
    cout <<"Earthquake is considered to be a micro earthquake" <<endl;
}
else if(Magnitude <= 2.9)
{
    cout <<"Earthquake is considered to be a very minor" <<endl;
}
else if(Magnitude <= 3.9)
{
    cout <<"Earthquake is considered to be a minor earthquake" <<endl;
}
else if(Magnitude <=4.9)
{
    cout <<"Earthquake is considered to be a light earthquake" <<endl;
}
else if(Magnitude <= 5.9)
{
    cout <<"Earthquake is considered to be a moderate earthquake" <<endl;
}
else if(Magnitude <= 6.9)
{
    cout <<"Earthquake is considered to be a strong earthquake" <<endl;
}
else if(Magnitude <= 7.9)
{
    cout <<"Earthquake is considered to be a major earthquake" <<endl;
}
else if(Magnitude <= 9.9)
{
    cout <<"Earthquake is considered to be a great earthquake" <<endl;
}
else if(Magnitude == 10)
{
    cout <<"Erathquake is considered to be a metoeic earthquake" <<endl;
}
else if(Magnitude > 10)
{
    cout << "There are no greater than ten" <<endl;
}
return 0;
}

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
	    
	    ALL EXERCISES 
	    

//////////////////////////////////

Lecture 3

Print:

#include <iostream>
using namespace std;

int main() {

cout << "Name:"  <<endl;

cout << "Age:"   <<endl;

cout << "Current Address:"  <<endl;

cout << "Permanent Address:" <<endl;

}

//////////////////////////////

Lecture 4

#include <iostream>
using namespace std;

int main() {
	cout <<"How many USB sticks I can buy in 50 aed?";
    cout <<" 8 USB sticks and you have a 2 dirhams change....";
	return 0;
}



/////////////////////////////////

Lecture 5

Biography:

#include <iostream>
#include <string>
using namespace std;

int main()
{
    string age, address, name;
   
    cout << "Enter your name: \n"; 
    cin >> name;
    cout << "\nEnter your age: \n";
    cin >> age;
    cout << "\nEnter your address:\n" << address;
    cin >> address;
    cout << "\nYour name is: \n" << name;
cout << "\nYour age is: \n" << age;
cout << "\nYour address is: \n" << address;
}

Temperature (fahrenheit to celcius):

#include <iostream>
#include <string>
using namespace std;

int main()
{
 double x;
    double y;
    cout << "Enter the temperature in Fahrenheit to be converted into celcius\n";
    cin >> x;
    y = (x - 32) * 0.5556;
    cout << "The temperature in Celcius is: " << y << endl;
}

Temperature (celcius to fahrenheit):

#include <iostream>
using namespace std;

int main()
{
 double x;
    double y;
    cout << "Enter the temperature in Celcius to be converted into fahrenheit\n";
    cin >> x;
    y = ( x * 9.0) / 5.0 + 32; 
    cout << "The temperature in Fahrenheit is: " << y << endl;
}

Circles:

#include <iostream>
int main()
{
   int circle_radius;
   float PI_VALUE=3.14, circle_area, circle_circumf;

   printf("\nEnter radius of circle: ");
   
   scanf("%d",&circle_radius);
   
   circle_area = PI_VALUE * circle_radius * circle_radius;
   printf("\nArea of circle is: %f",circle_area);

   circle_circumf = 2 * PI_VALUE * circle_radius;
   printf("\nCircumference of circle is: %f",circle_circumf);

}

Rectangle/Triangle/Square:

#include <iostream>
#include <string> 
using namespace std;

int main() {
   double length, width, rect, tri, sq;
    cout << "\nCalculating the area of Rectangle, Triangle and Square shapes\n";
    cout << "Enter the length:\n";
       cin >> length;
    cout << "\nEnter the width : \n";
    cin >> width;
rect = length * width;
tri = (length * width) * 0.5; sq= length*length;
    cout << "\nThe area of rectangle : \n" << rect;
    cout << "\nThe area of triangle: \n" << tri;
}


//////////////////////////////////////////

Lecture 6

It's my birthday:

#include <iostream>
using namespace std;

int main() {
    
bool myBirthday = true; int age = 18;
if (myBirthday == true) { age++;
cout << "It is my birthday. I am " <<
age << " years old";
} else {
cout << "It is not my birthday" <<
endl; }
return 0;
}

/// Odd or Even ///
#include using namespace std;
int main () { int n;
cout << "Enter an integer: "; cin >> n;
if ( n % 2 == 0) cout << n << "is even."; else cout << n << " is odd.";
return 0; }

/// Number Checker ///
#include using namespace std;
int main () {
int num; cout << "Enter the number to checked : "; cin >> num; if(num >=0){ cout << num << " is a positive number."; } else cout << num << " is a negative number."; return 0; }

/// Profit or Loss ///
#include using namespace std;
int main (){
int cp,sp,profit,loss; cout <<"enter cost price:" <<endl; cin >> cp; cout <<"enter selling price:" <<endl; cin >> sp; if (sp>cp) { profit = sp - cp; cout << "profit" << profit <<endl; } else if(cp>sp) { loss = cp - sp; cout << " loss of " << loss << endl; } else { cout << " no profit no loss."; } return 0; }

/// Name that Shape ///
#include using namespace std;
int main (){
int sides; cout << "Enter the sides of shape" <<endl; cin>>sides;
if(sides == 1) { cout << "The shape does not exist" <<endl; } if(sides == 2) { cout << "The shape does not exist" <<endl; } if(sides == 3) { cout << "The shape is triangle" <<endl; } if(sides == 4) { cout << "The shape is square" <<endl; } if(sides == 5) { cout << "The shape is pentagon" <<endl; } if(sides == 6) { cout << "The shape is hexagon" <<endl; } if(sides == 7) { cout << "The shape is heptagon" <<endl; } if(sides == 8) { cout << "The shape is octagon" <<endl; } if(sides == 9) { cout << "The shape is nonagon" <<endl; } if(sides == 10) { cout << "The shape is decagon" <<endl; } if(sides > 10) { cout << "error" <<endl; } return 0; }
/////////////////////////////////////////////////

Lecture 7

/// Mark my words ///
#include using namespace std;
int main (){
int percentage; cout <<"Enter the percentage:" <<endl; cin>>percentage;
if(percentage >= 70) { cout <<"The letter grade is A" <<endl; } if ((percentage > 60) && (percentage < 69)) { cout <<"The letter grade is B" << endl; } if ((percentage > 50) && (percentage < 59)) { cout <<"The letter grade is C" << endl; } if ((percentage > 40) && (percentage < 49)) { cout <<"The letter grade is D" << endl; } if (percentage < 40) { cout <<"The letter grade is F" << endl; } return 0; }
/// Starting a Band ///
#include using namespace std;
int main() { bool musicalfriend = true; bool nonmusicalfriend = false; // This is the nested if-else statement that governs the decisions if (musicalfriend) { if (nonmusicalfriend) { cout << "Do you want to be the guitarist of the band?" <<endl; } else { cout << "Do you want to be the guitarist of the band?" << endl; } } else { cout << "okay, thank you :D" << endl; }
int answer; cout << "Write your answer: 99 - Yes or 00 - No 55 - I want to be the drummer of the band:" <<endl; cin>>answer;
if(answer == 99) { cout <<"Welcome to our band! You are now qualified <333" <<endl; } if(answer == 00) { cout <<"okay, thank you for your time!:D" <<endl; } if(answer == 55) cout <<"Sure! You are qualified as the drummer!!! Welcome, cool XD" <<endl; return 0; }
/// Killing Time ///
#include using namespace std;
int main (){
int minutes; cout <<"How many minutes will you wait for your friend? She said __ minutes: Enter the minutes" <<endl; cin>> minutes;
if(minutes >= 15 ) { cout <<"Oh I will wait too long so I have decided to buy some things. :)" <<endl; cout <<"Cashier: Hi madam! your total bill is 170 dhs. (I pay my 200 dhs money)" <<endl; cout <<"Uhmm I still have 30 dhs change" <<endl; cout <<"Imma buy coffee and go for a walk" <<endl; } if (minutes < 15) { cout <<"Oh She will come sooner so I have decided to sit in the food zone and wait :)" << endl; }
return 0; }
/// Earthquake ///
#include using namespace std; int main() { int Magnitude; cout <<"Enter the Magnitude of the Earthquake:"; cin >> Magnitude;
if(Magnitude < 2.0) { cout <<"Earthquake is considered to be a micro earthquake" <<endl; } else if(Magnitude <= 2.9) { cout <<"Earthquake is considered to be a very minor" <<endl; } else if(Magnitude <= 3.9) { cout <<"Earthquake is considered to be a minor earthquake" <<endl; } else if(Magnitude <=4.9) { cout <<"Earthquake is considered to be a light earthquake" <<endl; } else if(Magnitude <= 5.9) { cout <<"Earthquake is considered to be a moderate earthquake" <<endl; } else if(Magnitude <= 6.9) { cout <<"Earthquake is considered to be a strong earthquake" <<endl; } else if(Magnitude <= 7.9) { cout <<"Earthquake is considered to be a major earthquake" <<endl; } else if(Magnitude <= 9.9) { cout <<"Earthquake is considered to be a great earthquake" <<endl; } else if(Magnitude == 10) { cout <<"Erathquake is considered to be a metoeic earthquake" <<endl; } else if(Magnitude > 10) { cout << "There are no greater than ten" <<endl; } return 0; }

////////////////////////////////////////////

Lecture 8

DAYS OF THE MONTH:

#include <iostream>
using namespace std;

int main() {
    int  month;
	cout << "Type the month number (1-12):" << endl;
	cin >> month;
	
	switch ( month) {
	    case 1:
	        cout << "January - 31 days" << endl;
	            break;
	   case 2: mecout
	       cout << "February - 28 days" << endl;
	       break;
	     case 3:
	       cout << "March - 31 days" << endl;
	       break;
	        case 4:
	       cout << "April - 30 days" << endl;
	       break;
	        case 5:
	       cout << "May - 31 days" << endl;
	       break;
	        case 6:
	       cout << "June - 30 days" << endl;
	       break;
	        case 7:
	       cout << "July - 31 days" << endl;
	       break;
	        case 8:
	       cout << "August - 31 days" << endl;
	       break;
	        case 9:
	       cout << "September - 30 days" << endl;
	       break;
	        case 10:
	       cout << "October - 31 days" << endl;
	       break;
	        case 11:
	       cout << "November - 30 days" << endl;
	       break;
	        case 12:
	       cout << "December - 31 days" << endl;
	       break;
	   default:
	       cout << "That input was not recognized" << endl; 
	}
	return 0;
}

/////////// FUEL ME UP//////////

#include <iostream>
using namespace std;

int main() {
	cout << "Type the fuel type:" << endl;
	char fuel;
	cin >> fuel;
	
	switch (fuel) {
	    case 'P':
	    case 'p': 
	        cout << "Petrol: Dh2. 44 per litre " << endl;
	            break;
	   case 'D':
	   case 'd':
	       cout << "Diesel: Dh 2.51 AED per litre " << endl;
	       break;
	   default:
	       cout << "invalid input" << endl; 
	}
	return 0;
}


////////// SWITCHING TEMPERATURE ////////

#include<iostream>
using namespace std;
int main()
{
  int t;
  cout<<"Enter 11 = For Celsius To Fahrenheit. \n";
  cout<<"Enter 22 = For Fahrenheit To Celsius. \n";
  cout<<"Enter 33 = For Exit\n\n";
  cout<<"Enter Your Choice \n ";
  cin>>t;
  switch(t)
   { 
    double cel,feh;
    case 11: cout<<"Enter The Temperature In Celsius\n";
      cin>>cel;
      feh=(cel*9/5)+32;
      cout<<"\nTemperature In Fahrenheit Is = "<<feh ;
    break;
   
   case 22: cout<<"Enter The Temperature In Fahrenheit\n";
      cin>>feh;
      cel=(feh-32)*5/9;
      cout<<"\nTemperature In Celsius Is = "<<cel ;
    break;
      
   case 33:exit(0);
   
   default:
   cout<<"\nInvalid\n";
    break;   
	return 0;
}
}

/////////// SWITCH GRADE CALCULATOR ////////////

#include <iostream>
#include <string>
using namespace std;

int main() {
    int  grade;
	cout << "Type your full name:" << endl;
	string name;
	getline(cin, name);
	
	cout << "Type your grade:" << endl;
	cin >> grade;
	
	switch (grade) {
	 
	  	    
	  	    case 35:
	  	    case 36:
	  	    case 37:
	  	    case 38:
	  	    case 39:
	  	    {
	  	 
	  	    cout << "Your letter grade is F" <<endl;
	  	    break;
	  	    }
	  	    case 40:
	  	    case 41:
	  	    case 42:
	  	    case 43:
	  	    case 44:
	  	    case 45:
	  	    case 46:
	  	    case 47:
	  	    case 48:
	  	    case 49: 
	  	    {
	  	    cout << "Your letter grade is E" <<endl;
	  	    break;
	}
	  	    case 50:
	  	    case 51:
	  	    case 52:
	  	    case 53:
	  	    case 54:
	  	    case 55:
	  	    case 56:
	  	    case 57:
	  	    case 58:
	  	    case 59:
	  	    {
	  	    cout << "Your letter grade is D" <<endl;
	  	    break;
	  	    }
	  	    case 60:
	  	    case 61:
	  	    case 62:
	  	    case 63:
	  	    case 64:
	  	    case 65:
	  	    case 66:
	  	    case 67:
	  	    case 68:
	  	  {
	  	    cout << "Your letter grade is C" <<endl;
	  	    break;
	  	  } 
	  	    
	  	    case 70:
	  	    case 71:
	  	    case 72:
	  	    case 73:
	  	    case 74:
	  	    case 75:
	  	    case 76:
	  	    case 77:
	  	    case 78:
	  	    case 79:
	  	    {
	  	    cout <<"Your letter grade is B" <<endl;
	  	    break;
	  	    }
	  	    
	  	    case 80: 
	  	    case 81:
	  	    case 82: 
	  	    case 83:
	  	    case 84:
	  	    case 85:
	  	    case 86:
	  	    case 87:
	  	    case 88:
	  	    case 89:
	  	    case 90:
	  	    case 91:
	  	    case 92:
	  	    case 93:
	  	    case 94:
	  	    case 95:
	  	    case 96:
	  	    case 97:
	  	    case 98:
	  	    case 99:
	  	    case 100:
	  	    {
	  	    cout <<"Your letter grade is A" <<endl;
	  	    break;
	  	    }
	  	    
	  	   default:
	  	   {
	  	    cout <<"Invalid" <<endl;
	  	    break;
	  	   }
	 
	}  
	  	    return 0;
	  	}

//////////////////////////////

Lecture 9 

#include <iostream>
using namespace std;

int main() {
   int count = 1;
   while(count <= 1000){
       cout << count << endl;
       count ++;
   }
	return 0;
}

//////////////////////////////////////////////////////////

#include <iostream>
using namespace std;

int main() {
   cout << "Enter a whole number: " <<
   endl; int userNum;
   cin >> userNum;
   
   int count = 1;
   while(true){
       cout << count << endl;
       if(count == userNum){
           break;
       }
       count++;
   }
	return 0;
}

//////////////////////////////////////////////////////////////

#include <iostream>
using namespace std;

int main() {
   cout << "Enter a whole number: " <<endl; 
   int userNum;
   cin >> userNum;
   
   int count = 1;
   while(count <= userNum){
       cout << count << endl;
       count++;
   }
	return 0;
}

////////////////////////////////////////////

#include <iostream>
using namespace std;

int main() {

cout << "Enter your age" << endl; int age;
cin >> age; while(cin.fail()){
cout << "Invalid input.\nPlease enter a valid age:" << endl; cin.clear();
cin.ignore(1000, '\n');
cin >> age; }
cout << "Your age is: " << age;
	
	return 0;
}

//////////////////////////////////////////////

#include <iostream>
using namespace std;

int main() {
    
   float myNum = 20;
   while(myNum > 0){
       
       cout << myNum << endl;
       myNum = myNum - 0.5;
}
	return 0;
}
/////////////////////////////////////////////////

#include <iostream>
#include <string>
using namespace std;

int main() {
	string password ="1234password";
	string userInput;

	    cout << "Enter your password" << endl;
	    cin >> userInput;
	while(password != userInput);
}
	cout << "Welcome to the super secure banking area" <<endl;
	
	return 0;
}
//////////////////////////////////////////////////////

int main() {
  string password = "1234password";
  string userInput;
do{ cout << "Enter your Password" << endl; cin >> userInput; 
}while(password != userInput); cout << "Welcome to the super secure banking area" << endl; 
	return 0;
}

///////////////////////////////////////////////////////

#include <iostream>
#include <string>
using namespace std;

int main() {
	string password ="1234password";
	string userInput;
	

	    cout << "Enter your password" << endl;
	    cin >> userInput;
	    
	while(password != userInput){
	cout << "Enter your password" <<endl;
	cin >> userInput;
	}
	cout <<"Welcome to the super secure banking area" <<endl;
	
	return 0;
}

	OCT 26 

Reverse 9 times table:

#include<iostream>
using namespace std;
int main()
{
    int i,n=1,m,a;
    cout<<"\nEnter the limit:";
    cin>>i;
    cout<<"\nEnter the table's number:";
    cin>>a;
    while(i>=n)
    {
        cout<<"\n"<<i<<"*"<<a<<"="<<i*a;
        i--;
    }
    return 0;
}

The Pointless Box:

#include <iostream>
using namespace std;
int main(){
   int i=1;
   cout << "Enter numbers 1 and 2:" <<endl;
   while(i<=1){
      cout<<"You have entered number: "<<i<<endl; i++;
   while (i<=2){
      cout<<"You have entered number: "<<i<<endl; i++;
      }
   }
}


Input Improvement: ()

#include <iostream>
using namespace std;

int main() {
	char input;
	do{
	    cout << "Would you like to Quit (Y/N)" <<endl;
	 cin >> input;
}while( (input != 'Y') && (input != 'N') );
	return 0;
}
	
	OCT 31 

#include<iostream>
using namespace std;

int main()
{
        int mark[5], i;
        float sum=0;
        cout<<"\nEnter marks obtained in Science, Moral Ed, Arabic, Maths , Filipino : \n";
        for(i=0; i<5; i++)
        {
            cout<<"\nEnter mark[ "<<i+1<<" ] ";
                cin>>mark[i];
                sum=sum+mark[i];
        }

        float avg=sum/5;
        float perc;
        perc=(sum/500)*100;
        cout<<"\nAverage Marks of 5 Subjects = [ "<<avg<<" ] \n";
        cout<<"\nPercentage in 5 Subjects = [ "<<perc<<"% ] \n";

        return 0;
}
	NOV 7

#include <iostream>
using namespace std;

int main() {
	for(int x = 0; x < 10; x++){
	    cout <<"X is " << x << "\n";
	}
	return 0;
}

///////////

#include <iostream>
using namespace std;

int main() {
	for(int x = 10 ; x >= 0; x--){
	    cout << x << endl;
	    
	    if (x == 0)
	    cout << "You have lift of";
	}
	return 0;
}

///////////

#include <iostream>
using namespace std;

int main() {
	for(int i=0; i<5; i++) {
	for (int j=0; j<5; j++){
	    cout << "☆";
	}
	cout << endl;
	}
	return 0;
}

/////////////

#include <iostream>
using namespace std;

int main() {
	for(int i = 20 ; i <= 24; i++){
	    
	    if (i % 2 == 0){
	    cout << i<<" - even" <<endl;
	    } else{
	        cout <<i<<" - odd" <<endl;
	    }
	}

	return 0;
}

////////////

NOV 9: All Exercises

Descending stars, seven lines:

#include <iostream>
using namespace std;

int main() {
	for(int i=1; i<=7; i++) {
	for (int j=i; j<=7; j++){
	    cout << "*";
	}
	cout << endl;
	}
	return 0;
}

Rising Stars, Five lines:

#include <iostream>
using namespace std;

int main() {
	for(int i=1; i<6; i++) {
	for (int j=1; j<= i; j++){
	    cout << "*";
	}
	cout << endl;
	}
	return 0;
}

Rising and Falling Stars:

#include <iostream>
using namespace std;

int main() {
	for(int i=1; i<6; i++) {
	for (int j=1; j<= i; j++){
	    cout << "*";
	}
	cout << endl;
	}
	for(int i=1; i<=7; i++) {
	for (int j=i; j<=7; j++){
	    cout << "*";
	}
	cout << endl;
	}

	return 0;
}



Cubes:

#include <iostream>
using namespace std;

int main()
 {
    int i,ctr;
    printf("Input number of terms : ");
    scanf("%d", &ctr);
    for(i=1;i<=ctr;i++)
    {
	 printf("Number is : %d and cube of the %d is :%d \n",i,i, (i*i*i));     
    }
 }

Find the 9's:

#include <iostream>
using namespace std;

int main()
{
    int i, sum = 0;
    cout << "Find the number and sum of all integer between 100 and 200, divisible by 9:" <<endl;
    cout << "Numbers between 100 and 200, divisible by 9:" << endl;
    for (i = 101; i < 200; i++) 
    {
        if (i % 9 == 0) 
        {
            cout << " " << i;
            sum += i;
        }
    }
    cout << "\n The sum : " << sum << endl;
}

Lecture 10

10: Some Counting

#include<iostream>
using namespace std;
int main(){
 for(int i=50; i>=0; i--){
 cout<<i<<" ";
 }
}
#include<iostream>
using namespace std;
int main(){
 for(int i=30; i<=50; i++){
 cout<<i<<" ";
 }
}

#include<iostream>
using namespace std;
int main(){
 
 int i=50;
 while(i>=10){
 cout<<i<<" ";
 i -= 2;
 }


}

#include<iostream>
using namespace std;
int main(){
 
 int i=100;
 while(i<=200){
 cout<<i<<" ";
 i += 5;
 }


}


11: Odd or Even

#include <iostream>
using namespace std;

int main() {
	for(int i = 20 ; i <= 24; i++){
	    
	    if (i % 2 == 0){
	    cout << i<<" - even" <<endl;
	    } else{
	        cout <<i<<" - odd" <<endl;
	    }
	}

	return 0;
}

12: Iterate through a word

#include <iostream>
#include <string>
using namespace std;

string myWord ="ARSH";
int main() {
    cout <<myWord.at(0)<<endl;
    cout <<myWord.at(1) <<endl;
    cout <<myWord.at(2) <<endl;
    cout <<myWord.at(3) <<endl;
	cout << endl;
	return 0;
}

13: Seven stars, seven lines

#include <iostream>
using namespace std;

int main() {
	for(int i=0; i<7; i++) {
	for (int j=0; j<7; j++){
	    cout << "*";
	}
	cout << endl;
	}
	return 0;
}
NOV 14

#include <iostream>
using namespace std;

int main() {
	int y;
cout << "Enter a number you want the table of: " << endl;
cin >> y;
while (cin.fail())
{ cout << "Invalid command enter the number again: " << endl;
cin.clear();
cin.ignore(1000, '\n');
cin >> y;
}
for (int x = 0; x <= 10; x++)
{ cout << y << " x " << x << " = " << y * x << endl; 
    
}
}

////////

#include <iostream>
using namespace std;

int main() {
	for(int i=1; i<=5; i++) {
	for (int j=i; j<=5; j++){
	    cout << "*";
	}
	cout << endl;
	}

	return 0;
}

////////

#include <iostream>
using namespace std;

int main() {
	for(int i=1; i<6; i++) {
	for (int j=1; j<= i; j++){
	    cout << "*";
	}
	cout << endl;
	}
	return 0;
}

//////

#include <iostream>
using namespace std;

int main() {
	for(int i=1; i<=5; i++) {
	for (int j=i; j<=5; j++){
	    cout << "*";
	}
	cout << endl;
	}
for(int i=1; i<6; i++) {
	for (int j=1; j<= i; j++){
	    cout << "*";
	}
	cout << endl;
	}
	return 0;
}

///////
	    
	    
NOV 16

1 ///////////

#include <iostream>
#include <string>
using namespace std;
int main()
{
	int i = 1, j=1;
	while (i <= 5)
	{ 
	int j =1;	
	while (j = 1)
		{
			cout << "*"; //print 5 stars
			j++;
		}
		cout << endl;  
		i++;
	}

}

2 //////////// 

#include <iostream>
#include <string>
using namespace std;
int main()
{
	int y,x= 1;
	cout << "Enter a number you want the table of: " << endl;
	cin >> y;
	while (cin.fail())
	{
		cout << "Invalid command enter the number again: " << endl;
		cin.ignore(1000, '\n');
		cin >> y;
		}
	while (x <= 10)
	{
		cout << y << " x " << x << " = " << y * x << endl;
		x++;
	}

}

3 //////////// 

#include<iostream> 
#include<string> 
using namespace std;
int main()
{
	int y, z = 1;
	cout << "enter a number you want the factorial of: " << endl;
	cin >> y;
	while (cin.fail() || y <= 0)
	{
		cout << "invalid command enter the number again: " << endl;
		cin.clear();
		cin.ignore(1000, '\n');
		cin >> y;
	}

	for (int x = 1; x <= y; x++)

		z = z * x;
	cout << "factorial is: " << z;

}


4 /////////////

#include <iostream>
#include <string>
using namespace std;
int main()
{
	int x = 0;
	int sum = 0;
	do
	{
		if (x % 9 == 0)
		{
			cout << "\nNumber is " << x << " ";
			sum = sum + x;
			} x++;
		
	}
	while (x <= 200);
	cout << endl;
	cout << "\nThe sum is " << sum << endl;
}

5 /////////////

#include <iostream>
#include <string>
using namespace std;
int main()
{
	int x = 0;
	int sum = 0;
	do
	{
		if (x % 9 == 0)
		{
			cout << "\nNumber is " << x << " ";
			sum = sum + x;
			} x++;
		
	}
	while (x <= 200);
	cout << endl;
	cout << "\nThe sum is " << sum << endl;
}

6 ////////////// 

#include <iostream>
#include <string>
using namespace std;
int main()
{
	for (int x = 20; x <= 24; x++)
	{
		if (x %2 !=0)
			cout << x << " - even" << "\n";
		else
			cout << x << " - odd" << "\n";
	}

}

7 /////////////

#include <iostream>
using namespace std;
int main()
{
	string m;
	cout << "Do you want to go to the expo? type Y for yes and N for no" << endl;
	string mall;
	cin >> mall;
	if (mall == "Y" || mall == "y")
	{
		cout << "Enjoy" << endl;
	}
	else if (mall == "N" || mall == "n")
	{
		cout << "Unfortunately its mandatory, you have to go" << endl;

	}
	else
	{
		cout << "Incorrect command" << endl;

	}
}

NOV 21

#include <iostream>
using namespace std;

int ages[5];
	
	ages[0] = 19;
	ages[1] = 23;
	ages[2] = 22;
	ages[3] = 30;
	ages[4] = 18;

	return 0;
}

///////

#include <iostream>
using namespace std;

int main() {
	int array [5] = {19, 23, 22, 30, 18};
	int array [] = {19, 23, 22, 30, 18};
	return 0;
}

////////

#include <iostream>
using namespace std;

int main() {
	int heartRates[8] = {54, 60, 71, 59, 62, 63, 60, 58 };
	for (int i = 0; i < 8; i++){
	    cout << heartRates[i] <<endl;
	}
	return 0;
}

#include <iostream>
#include <string>
using namespace std;
int main()
{
    //declaring and initialising string array for the months
    string months[12] = { "January", "February", "March","April","May","June","July","August","September","October","November","December" };
    
    //displaying the values stored in the months array
    for (int i = 0; i < 12; i++)
    {
        cout << months[i] << endl;
    }
}
///////////
#include <iostream>
using namespace std;

int main()
{
    cout << "Enter marks for five subjects" <<endl;
    int marks[5];
    int sum=0;
    for (int i = 0; i < 5; i++)
    {
        cout << "grade:" << endl;
        cin >> marks[i];
        while (cin.fail() || marks[i]>100 || marks[i]<0) {
            cout << "invalid command, enter the marks again\n";
            cin.clear();
            cin.ignore();
            cin >> marks[i];
        }

          sum = sum + marks[i];
        }
    cout << "Your average is: " << sum / 5<<endl;
}

///////
	    
	    
	    
	    
