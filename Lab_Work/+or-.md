# Positive or Negative
Write a CPP program to check whether a number is positive or negative.
```cpp
#include <iostream>
using namespace std;

int main() {
cout <<"-----TO CHECK WEATHER THE INTEGER GIVEN IS POSITIVE OR NEGATIVE-----"<<endl;
	int x;
	cout << "Enter the number: ";
	cin >> x;

	if(x>0) {
		cout << x <<" is POSITIVE."<<endl;
	}
	else if(x<0) {
		cout << x <<" is NEGATIVE."<<endl;
	}
	else {
		cout << x <<"is ZERO."<<endl;
	}

return 0;
}
```
