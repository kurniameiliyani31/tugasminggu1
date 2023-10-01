# tugasminggu1
#include <iostream>
using namespace std;

int main() {
    // Deklarasi variabel
    int angka = 5;
    
    // Loop menggunakan for
    for (int i = 1; i <= angka; i++) {
        // Penggunaan if
        if (i % 2 == 0) {
            cout << i << " adalah angka genap" << endl;
        } else {
            cout << i << " adalah angka ganjil" << endl;
        }
    }
    
    // Loop menggunakan while
    int j = 1;
    while (j <= angka) {
        cout << "Loop while ke-" << j << endl;
        j++;
    }
    
    // Loop menggunakan do-while
    int k = 1;
    do {
        cout << "Loop do-while ke-" << k << endl;
        k++;
    } while (k <= angka);
    
    // Array satu dimensi
    int arrSatuDimensi[] = {1, 2, 3, 4, 5};
    
    // Array multidimensi
    int arrMultiDimensi[2][3] = {{1, 2, 3}, {4, 5, 6}};
    
    // Input
    int inputAngka;
    cout << "Masukkan sebuah angka: ";
    cin >> inputAngka;
    
    // Output
    cout << "Anda memasukkan angka: " << inputAngka << endl;
    
    // Komentar
    // Ini adalah komentar satu baris
    
    /*
    Ini adalah
    komentar
    beberapa baris
    */
    
    return 0;
}
