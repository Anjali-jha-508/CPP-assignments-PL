# Information about Book
Write a CPP program to display information of a Book using class.
```cpp
#include <iostream>
#include <string>
using namespace std;

class Book {
	int publishNo, pages;
	string author, title, genre;
	float cost;
public:
	Book() {
		publishNo = 0;
		author = " ";
		title = " ";
		genre = " ";
		pages = 0;
		cost = 0;
	}
	Book(int epublishNo, int epages, string eauthor, string etitle, string egenre, float ecost) {
		publishNo = epublishNo;
		author = eauthor;
		title = etitle;
		genre = egenre;
		pages = epages;
		cost = ecost;
	}
	void display(){
		cout << "Publishing NUmber: " << publishNo << endl;
		cout << "Author of the book: " << author << endl;
		cout << "Title of the book: " << title << endl;
		cout << "Genre of the book: " << genre << endl;
		cout << "Number of pages in the book: " << pages << endl;
		cout << "Cost of the book: " << cost << endl;
	}
};

int main() {
	Book b1;
	b1.display();

	Book b2(3202, 284, "Coollen", "November-9", "Fiction", 350.78);
	b2.display();

	return 0;
}
```
