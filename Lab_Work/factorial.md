# Factorial
Write a CPP program to calculate factorial of a number.
```cpp
#include <iostream>
using namespace std;

int main() {
	cout << "---CALCULATE FACTORIAL---"<< endl;
	int n;
    cout << "Enter a natural number: ";
    cin >> n;
    long long int factorial = 1;
    
    
	for(long long int i = 1; i<=n; i++) {
    factorial = factorial * i;
    }
  
   cout << endl<< "Factorial of " << n <<" is " << factorial;
    return 0;
}

//on executing got to know that this code shows accurate result only for numbers from 1 to 39.
//from 40, the answer obtained becomes negative.
```
