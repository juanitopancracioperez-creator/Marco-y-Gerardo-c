#include <iostream>
#include <cmath>
using namespace std;

int main() {
    double a, b, c, d;
    double radianes, grados;
    // código de marco PT y Gerardo 
    cout << "Ingresa el ángulo: ";
    cin >> a;
    
    // Convertir a radianes y grados
    radianes = (a * 3.1416) / 180;
    grados = a;
    
    cout << "\n--- En Radianes ---" << endl;
    b = log(radianes);
    c = sin(radianes);
    d = cos(radianes);
    
    cout << "log: " << b << endl;
    cout << "sin: " << c << endl;
    cout << "coseno: " << d << endl;
    cout << "Tangente: " << tan(radianes) << endl;
    
    cout << "Sen^-1: " << asin(radianes) << endl;
    cout << "Cos^-1: " << acos(radianes) << endl;
    cout << "tan^-1: " << atan(radianes) << endl;
    
    cout << "SecantA: " << 1/cos(radianes) << endl;
    cout << "Cosecant: " << 1/sin(radianes) << endl;
    cout << "Cotangente: " << 1/tan(radianes) << endl;
    
    cout << "\n--- En Grados ---" << endl;
    b = log(grados);
    c = sin(grados * 3.1416 / 180);
    d = cos(grados * 3.1416 / 180);
    
    cout << "log: " << b << endl;
    cout << "sin: " << c << endl;
    cout << "coseno: " << d << endl;
    cout << "Tangente: " << tan(grados * 3.1416 / 180) << endl;
    
    cout << "Sen^-1: " << asin(grados) * 180 / 3.1416 << endl;
    cout << "Cos^-1: " << acos(grados) * 180 / 3.1416 << endl;
    cout << "tan^-1: " << atan(grados) * 180 / 3.1416 << endl;
    
    cout << "Secantes: " << 1/cos(grados * 3.1416 / 180) << endl;
    cout << "Cosecantes: " << 1/sin(grados * 3.1416 / 180) << endl;
    cout << "Cotangente: " << 1/tan(grados * 3.1416 / 180) << endl;
    
    return 0;
} 