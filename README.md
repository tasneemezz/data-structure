# data-structure
#include<iostream>
using namespace std;
class Node {
public:
	char data;
	Node* next;
};
int main() {
	Node* first = new Node();
	Node* second = new Node();
	Node* third = new Node();
	Node* fourth = new Node();
	Node* fifth = new Node();
	Node* six = new Node();
	Node* seven = new Node();
	first->data = 'T';
	first->next = second;
	second->data = 'a';
	second->next = third;
	third->data = 's';
	third->next = fourth;
	fourth->data = 'n';
	fourth->next = fifth;
	fifth->data = 'e';
	fifth->next = six;
	six->data = 'e';
	six->next = seven;
	seven->data = 'm';
	cout << first->data;
	cout << second->data;
	cout << third->data;
	cout << fourth->data;
	cout << fifth->data;
	cout << six->data;
	cout << seven->data;








}
