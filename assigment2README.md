# data-structure
#include<iostream>
 using namespace std;
#define size 10
 class stack {
	 int array[size];
	 int top = -1;
 public:
	 void push(int value) {
		 if (top < size) {
			 top++;
			 array[top] = value;
		 }
		 else
			 cout << "is full";
	}
	 bool pop() {
		 if (top == size - 1) {
			 top--;
			 return true;
		 }
		 else
			 cout << "is empty";

	 }
 };
 int main() {
	 stack s;
	 s.push(5);
	 s.push(10);
	 s.pop();

 }
