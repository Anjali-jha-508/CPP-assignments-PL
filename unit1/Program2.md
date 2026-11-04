# Program 2
Example of Array: store student marks in array and display the marks

```cpp
#include <iostream>
#include <string>
using namespace std;

class Student { 
    int marks[3];
public:
    void getMarks() {
        cout << "Enter marks of Subject 1: ";
        cin >> marks[0];
        cout << "Enter marks of Subject 2: ";
        cin >> marks[1];
        cout << "Enter marks of Subject 3: ";
        cin >> marks[2];
    }
    void showMarks() {
        cout << "Marks: " << endl;
        for(int i=0; i<3; i++) {
            cout << marks[i] << endl;
        }
    }
};

int main() {
    cout << "Example of Array:" << endl << "Store student marks in array and display the marks" << endl;
    cout << "---STUDENT MARKS DISPLAY---" << endl;
        Student s1;
        s1.getMarks();
        s1.showMarks();
    
    return 0;
}

```
