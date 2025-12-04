# Assignment-
#include <iostream>
using namespace std;

int main() {
    int a, b, c, d, e;
    cout << "Enter five integers: ";
    cin >> a >> b >> c >> d >> e;

    int sum = a + b + c + d + e;
    float average = sum / 5.0;

    cout << "Sum = " << sum << endl;
    cout << "Average = " << average << endl;

    return 0;
}
