# Prime or Not
Write a CPP program to check whether a number is prime or not.

```cpp
#include <iostream>
using namespace std;

int main() {
    cout << "---PRIME NUMBER CHECKER---" << endl;
    int n;
    int isPrime = 1;

    cout << "Enter a positive integer: ";
    cin >> n;

    // Numbers less than or equal to 1 are not prime
    if (n <= 1) {
        isPrime = 0;
    } 
    else {
        // a prime number is only divisible by 1 and itself 
        // Check if n is divisible by any number from 2 to n-1
        for (int i = 2; i < n; i++) {
            if (n % i == 0) {
                isPrime = 0; // Found a factor, so it is not prime
            }
        }
    }

    // Output the result
    if(isPrime == 1) {
        cout << n << " is a prime number." << endl;
    } 
    else {
        cout << n << " is not a prime number." << endl;
    }

    return 0;
}
```
