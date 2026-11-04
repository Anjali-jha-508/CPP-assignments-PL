# Program 3
Array of Objects: Create array of objects

```cpp
#include <iostream>
#include <string>
using namespace std;

class Student {
    string name, surname;
public:
    void Display() {
        cout << "Enter Student Name: ";
        cin >> name >> surname;
        cout << "Hello " << name << endl;
    }
};

int main() {
    cout << "Array of Objects: Create array of objects" << endl;
    cout << "---STUDENT NAME DISPLAY for 3 different ---" << endl;

        Student s1[3];
        s1[0].Display();
        s1[1].Display();
        s1[2].Display();

    return 0;
}
```
