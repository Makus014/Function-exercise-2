# Function-exercise-2




//Root
#include <iostream>
#include <cmath>
using namespace std;

string function(double num) {
	for (int i = 1; i < 10; i++) {
		double result;
		double result1;
		result1 = 1.0 / i;
		result = pow(num, result1);
		cout << i << " The exponent for " << num << " is " << result << endl;
	}
	return "Code complete";
}

int main() {
	int number;
	cout << "Input any number" << endl;
	cin >> number;

	cout << function(number) << endl;


	return 0;
}










//exponent
#include <iostream>
#include <cmath>
using namespace std;

string function(double num) {
	for (int i = 1; i < 10; i++) {
		double result;
		result = pow(num, i);
		cout << i << " The exponent for " << num << " is " << result << endl;
	}
	return "Code complete";
}

int main() {
	int number;
	cout << "Input any number" << endl;
	cin >> number;

	cout << function(number) << endl;


	return 0;
}
