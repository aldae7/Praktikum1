#Praktikum1


#latihan1.cpp Program menghitung Luas persegi panjang

*Alur algoritma

1. mendeklarasikan variabel int, p, l sebagai input dan keliling; sebagai variabel hasil.
2. mengisi nilai variabel input panjang dengan cout << "masukkan panjang persegi panjang= "; cin >> p;
3. mengisi nilai variabel input lebar dengan cout << "masukkan lebar persegi panjang= "; cin >> l;
4. masukkan hasilnya keliling = p * l; cout << "keiiling persegi panjang adalah " << keliling; return 0;

Hasil Dari Codingan nya :

#include <iostream>

using namespace std;

int main () {
	int p,l,keliling;
	
	cout << "masukkan panjang persegi panjang= "; cin >> p;
	cout << "masukkan lebar persegi panjang= "; cin >> l;
	
	keliling = p * l;
	cout << "keliling persegi panjang adalah " << keliling;
	return 0;
}