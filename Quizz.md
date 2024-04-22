1. Tuliskan sebuah program yang mengeluarkan "Hello, World!" sebanyak n kali (di mana n adalah sebuah bilangan bulat non-negatif yang akan dimasukkan oleh pengguna) dengan: \
a. Foor loop \
b. While loop \
c. Do while loop 

2.a. Tuliskan keluaran (apa yang tercetak di layar) dari program-program di bawah ini pada kotak kosong di samping kanan program. Jika tidak ada keluaran, tuliskan: Tidak ada keluaran. Program-program di bawah ini sudah dipastikan lolos kompilasi.
```c++
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
```c++
#include <iostream>
using namespace std;

int main() {
    const int i = 3, j = 3;
    int arr[i][j] = {{1, 2, 3}, {4, 5, 6},{7, 8, 9}};
    for(int a = 0; a < 3; a++)
    {
        for(int b = 0; b < 3; b++)
        {
        cout << arr[a][b] << " ";
        }
        cout << endl;
    } 
	return 0;
}

```

```c++
#include <iostream>
using namespace std;

int main() {
  string letters[2][4] = {
    { "A", "B", "C", "D" },
    { "E", "F", "G", "H" }
  };
  
  cout << letters[0][2];
  return 0;
}
```

2.b. Tuliskan keluaran (apa yang tercetak di layar) dari program di bawah ini jika nilai N adalah 2 digit terakhir NRP Anda. Program sudah dipastikan lolos kompilasi.
```c++
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

3.a Buatlah fungsi IsVokal yang
- mempunyai parameter input sebuah character huruf
kecil ‘a’ sampai dengan ‘z’
- menghasilkan true jika character tersebut adalah vokal (‘a’, ‘i’, ‘u’, ‘e’, ‘o’)

3.b. Buatlah sebuah struct bernama `Peserta` yang memiliki data anggota sebagai berikut: `nama`, `umur`, `jenis_kelamin`, dan `nilai`. Buatlah sebuah program untuk mengisi data peserta sebanyak 3 peserta, kemudian tampilkan nama peserta yang memiliki nilai tertinggi.

4. Lengkapi bagian dari program berikut: \

a. Masukkan bagian yang hilang dari kode di bawah ini untuk menampilkan "Hello World".
```c++
int main() {
  `...` << "Hello World!";
  return 0;
}
```
b. Buat sebuah array tipe `string` bernama `cars`.
```c++
 `...` `...` [4] = {"Volvo", "BMW", "Ford", "Mazda"};
```
c. Cetak `i` selama `i` kurang dari 6
```c++
int i = 1;
 `...` (i < 6) {
  cout << i << "\n";
  `...`;
}
```
d. Buat sebuah fungsi bernama `myFunction` dan panggil fungsi tersebut di dalam `main()`.
```c++
void `...` () {
  cout << "I just got executed!";
}

int main() {  
  `...`;
  return 0;
}
```