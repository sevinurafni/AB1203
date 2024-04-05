1. Buatlah sebuah program yang menerima suhu air (dalam derajat celcius) dan menuliskan wujud air ke layar sebagai berikut:
- Jika suhu air <= 0 derajat, maka tuliskan “beku”
- Jika suhu air > 0 dan kurang dari 100 derajat, maka tuliskan “cair”
- Jika suhu air >= 100, maka tuliskan “uap”

2. Buatlah program untuk menghitung perkalian dari dua buah pecahan \
Spesifikasi program: \
– Program menerima masukan pecahan pertama berupa
pembilang dan penyebut \
– Kemudian program menerima pecahan kedua \
– Lalu program akan melakukan perkalian \
– Kemudian menampilkan hasilnya berupa pembilang dan penyebut hasil penjumlahan

3. Buatlah sebuah program yang membaca dari keyboard: \
– Panjang dari suatu persegi empat, misalnya p,  \
– Lebar dari suatu persegi empat, misalnya l \
• Asumsikan masukan panjang dan lebar selalu>0 \
• Selanjutnya program memeriksa: \
– Jika p sama dengan l, maka tuliskan ke layar “Bujur sangkar” \
– Jika p tidak sama dengan l, maka tuliskan ke layar “Persegi panjang”


4. Tuliskan keluaran program berikut ini:
```
#include <iostream>
using namespace std;
int main () {
int X;
X = 100;
if (X % 10 == 0) {
       cout << "XXX" << endl;
       if (X / 5 == 0) {
        cout << "aaa" << endl;
       }
       if (X % 11 == 1) {
             cout << "bbb" << endl;
        } 
} else {
	   cout << "YYY" << endl;
       if (X / 2 == 0) {
             cout << "ccc" << endl;
       }
       if (X % 3 == 1) {
       		 cout << "ddd" << endl;
        } 
}
	 return 0;   
}
```

5. Tuliskan keluaran (apa yang tercetak di layar) dari program di bawah ini jika N = 8. Program sudah dipastikan lolos kompilasi.
```
#include <iostream>
using namespace std;
int main () {
    int j, N, R;
    cin >> N;
    j = 1;
    R = 1;
    while (j <= N) {
        R = R * j;
        j = j + 2;
    }
    cout << R;
    return 0;
}
```

6. Buatlah fungsi IsVokal yang
- mempunyai parameter input sebuah character huruf
kecil ‘a’ s.d. ‘z’
- menghasilkan true jika character tersebut adalah vokal (‘a’, ‘i’, ‘u’, ‘e’, ‘o’)