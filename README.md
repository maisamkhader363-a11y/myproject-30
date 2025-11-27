#include<iostream>
#include<cmath>
using namespace std;
int main()
{
	int r, c;
	cout << "plz enter the number of rows" << endl;
	cin >> r;
	cout << "plz enter the number of columns" << endl;
	cin >> c;
	for (int i = 1; i <= r; i++) {
		for (int k = 1; k <= c; k++) {

			cout << i;
		}

		cout << "\n";
	}
}
