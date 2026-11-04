# Largest of 3
Write a CPP program to find out the largest number among the 3 given numbers.
```cpp
#include <iostream> 
using namespace std;  

int main() {     
    double num1, num2, num3;      // Taking input from the user  

    cout << "Enter number 1: ";     
    cin >> num1;     
    cout << "Enter number 2: ";     
    cin >> num2;     
    cout << "Enter number 3: ";     
    cin >> num3;  
        
    // Checking conditions to find the largest number   
    
    //number 1 is greater than or equal to both number 2 and number 3
    if (num1 >= num2 && num1 >= num3) {         
        cout << "The largest number is: " << num1 << endl;     
    }     
    //number 2 is greater than or equal to both number 1 and number 3
    else if (num2 >= num1 && num2 >= num3) {         
        cout << "The largest number is: " << num2 << endl;     
    }  
    //number 3 is greater than or equal to both number 1 and number 2   
    else {         
        cout << "The largest number is: " << num3 << endl;     
    }      

    return 0; 
}  
```
