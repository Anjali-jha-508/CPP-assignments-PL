# Even or Odd
Write a CPP program to check whether the number is even or odd.
```cpp
#include <iostream>
using namespace std;

int main(){
cout<<"---CHECK WEATHER THE INTEGER IS ODD OR EVEN---"<<endl;

int num;
cout<<"Enter the number: ";
cin>>num;
	if(num % 2 == 0){
		cout<< endl << num <<" is EVEN.";
	}
	else{
		cout<< endl << num <<" is ODD.";
	}
return 0;
}
```
