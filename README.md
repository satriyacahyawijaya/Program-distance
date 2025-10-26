#include <iostream>
#include <cmath>   
using namespace std;

int main() {
    double x1, y1, x2, y2;

    cout << "Masukkan koordinat titik pertama (x1): ";
    cin >> x1 ;
    cout << "Masukkan koordinat titik pertama (y1): ";
    cin >> y1 ;
    cout << "Masukkan koordinat titik kedua (x2): ";
    cin >> x2 ;
    cout << "Masukkan koordinat titik kedua (y2): ";
    cin >> y2 ;

    cout << "\ntitik pertama: " << "(" << x1 << "," << y1 << ")" ;
    cout << "\ntitik kedua: " << "(" << x2 << "," << y2 << ")" << endl;

    double distance = sqrt(pow(x2 - x1, 2) + pow(y2 - y1, 2));

    cout << "\nJarak antara kedua titik adalah: " << distance << endl;

    return 0;
}
