# Program 4

### 1: To Create a Rectangle class with private data members and define member functions both inside the class to calculate area and perimeter

```cpp
#include <iostream>
#include <string>
using namespace std;

class Rectangle {
    private:
        float length, breadth, area, perimeter;
    public:
        void getDimensions() {
            cout << "Enter length of rectangle: ";
            cin >> length;
            cout << "Enter breadth of rectangle: ";
            cin >> breadth;
        }
        void calculateArea() {
            area = length * breadth;
        }
        void calculatePerimeter() {
            perimeter = 2 * (length + breadth);
        }
        void displayResults() {
            cout << "----Rectangle Details----" << endl;
            cout << "Length: " << length << " units" << endl;
            cout << "Breadth: " << breadth << " units" << endl;
            cout << "Area: " << area << " square units" << endl;
            cout << "Perimeter: " << perimeter << " units" << endl;
        }
};

int main() {
    cout << "To Create a Rectangle class with private data members" << endl << "and define member functions both inside the class" << endl << "to calculate area and perimeter" << endl;
    cout << "---RECTANGLE AREA AND PERIMETER CALCULATOR---" << endl;

    Rectangle r1;
    r1.getDimensions();
    r1.calculateArea();
    r1.calculatePerimeter();
    r1.displayResults();

    return 0;
}
```

### 2: To Create a Rectangle class with private data members and define member functions outside the class to calculate area and perimeter

```cpp
#include <iostream>
#include <string>
using namespace  std;

class Rectangle {
private:
	float  length, breadth, area, perimeter;
public:
	void getDimensions();
	void calcArea();
	void calcPerimeter();
	void display();
};

void Rectangle::getDimensions() {
	cout << "Enter length of the rectangle: ";
	cin >> length;
	cout << "Enter breadth of the rectangle: ";
	cin >> breadth;
}

void Rectangle::calcArea() {
	area = length * breadth;
}

void Rectangle::calcPerimeter() {
	perimeter = 2*(length + breadth);
}

void Rectangle::display() {
    cout << "----Rectangle Details----" << endl;
	cout << "Length is: " << length <<endl;
	cout << "Breadth is: " << breadth <<endl;
	cout << "Area is: " << area <<endl;
	cout << "Perimeter is: "<< perimeter <<endl;
}

int main() {
    cout << "To Create a Rectangle class with private" << endl << "data members and define member functions outside" << endl << "the class to calculate area and perimeter";
    cout << "---RECTANGLE AREA AND PERIMETER CALCULATOR---" << endl;
        Rectangle r1;
        r1.getDimensions();
        r1.calcArea();
        r1.calcPerimeter();
        r1.display();

return 0;
}
```
