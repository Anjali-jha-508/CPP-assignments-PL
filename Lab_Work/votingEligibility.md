# Voting Eligibility
Write a CPP program to display voting eligibility of a person

```cpp
#include <iostream>
using namespace std;

int main() {
	int age;
	cout<<"-----Check voting age eligibility-----"<<endl;
	cout<<"Enter the age: ";
	cin >> age;
	
	if(age < 0) {
		cout << "Invalid Age!!!";
	}
	else if(age >= 18) {
		cout << "Eligible to vote.";
	}
	else {
		cout << "Minor - not eligible to vote.";
	}

	return 0;
}
```
