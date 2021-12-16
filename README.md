# Exercise-for-Functions

//first part (rooting)
		#include <iostream>
		#include <conio.h>
		#include <cmath>
		using namespace std;

		string Root(double user) {
			int i;
			float result;
			float result1;
			cout << "Rooting 1-10" << endl;
			for (i = 1; i <= 10; i++) {
				result1 = 1.0 / i;
				result = pow(user, result1);
				cout << user << " [" << i << "] " << result << endl;
			}
				return "Code is complete";

		}
		int main() {
			double user;
			cout << "Enter any number: "; cin >> user;
			cout << Root(user);
			return 0;
		}
  
//Second part (exponent)  
		#include <iostream>
		#include <conio.h>
		#include <cmath>
		using namespace std;

		string Exponent(double user) {
			int i;
			float result;
			float result1;
			cout << "exponent 1-10" << endl;
			for (i = 1; i <= 10; i++) {
				result = pow(user, i);
				cout << user << " [" << i << "] " << result << endl;
			}
				return "Code is complete";

		}
		int main() {
			double user;
			cout << "Enter any number: "; cin >> user;
			cout << Exponent(user);
			return 0;
		}
