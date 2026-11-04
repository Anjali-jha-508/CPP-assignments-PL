# Fibonacci 
Write a CPP program to print Fibonacci series.
```cpp
#include <iostream>
using namespace std;
int main() {
	int a = 1, b = 2, c = 0;
	cout << "Fibonacci Series upto 20 terms" << endl;
	cout << a << endl;
	cout << b <<endl;
	for (int i = 1; i < 20; i++) {
		c = a + b;
		cout << c << endl;
		a = b;
		b = c;
	}
return 0;
}
```
