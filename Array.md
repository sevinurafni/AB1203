## Apa itu array?

Array adalah struktur data yang digunakan untuk menyimpan elemen-elemen data sejenis dengan tipe data yang sama. Elemen-elemen dalam array diidentifikasi oleh indeks atau posisi mereka dalam array. Ukuran array didefinisikan pada saat deklarasi dan tidak dapat diubah setelahnya. Index array pada C++ dimulai dari 0. Artinya, elemen pertama dalam array memiliki indeks 0, elemen kedua memiliki indeks 1, dan seterusnya. Jadi, jika Anda memiliki array dengan ukuran n, indeksnya akan berkisar dari 0 hingga n-1.

## Penulisan array

Berikut adalah contoh mendeklarasikan array

```c++
// Deklarasi array dengan tipe data int dan ukuran 5
int angka[5];

nilai[0] = 32;
nilai[1] = 42;
nilai[2] = 76;
nilai[3] = 31;
nilai[4] = 57;


// Deklarasi dan inisialisasi array sekaligus
int nilai[] = {90, 85, 88, 92, 78};
```

selanjutnya adalah cara mengakses array,

```c++
// Mengakses dan menampilkan elemen array
cout << "Elemen ke-2 dari array nilai: " << nilai[1] << endl;
```
## Mengisi ulang Array

```c++
#include <iostream>

int main() {
    // isi awal array
    char huruf[5] = {'a', 'b', 'c', 'd', 'e'};

    // mengubah isi array
    huruf[2] = 'z';

    // mencetak isi array
    std::cout << "Huruf: " << huruf[2] << std::endl;

    return 0;
}
```


## Multidimensional Array

Array multidimensional adalah array dengan dua atau lebih dimensi.
Deklarasi dan Inisialisasi Array 2D:

```c++
// Deklarasi array 2D dengan tipe data int
int matriks[3][3] = {{1, 2, 3}, {4, 5, 6}, {7, 8, 9}};
```

## Mengambil Data dari Array Dua Dimensi
```c++
#include <iostream>

int main() {
    int matriks[3][3] = {
        {1, 2, 3},
        {4, 5, 6},
        {7, 8, 9}
    };

    std::cout << "Isi Data pada indeks ke-(1,0): " << matriks[1][0] << std::endl;

    return 0;
}
```

## Program Menghitung Rata-rata Nilai dengan Array

```c++
#include <iostream>

int main() {
    // Deklarasi array dan inisialisasi
    double nilai[] = {90.5, 85.0, 88.5, 92.0, 78.0};
    int jumlahNilai = 5;
    double totalNilai = 0.0;

    // Menghitung total nilai
    for (int i = 0; i < jumlahNilai; ++i) {
        totalNilai += nilai[i];
    }

    // Menghitung rata-rata nilai
    double rataRata = totalNilai / jumlahNilai;

    // Menampilkan hasil
    std::cout << "Total nilai: " << totalNilai << std::endl;
    std::cout << "Rata-rata nilai: " << rataRata << std::endl;

    return 0;
}
```

## Tugas
Buat program untuk menjumlahkan 2 matrik berikut: 
$$
A = \begin{pmatrix}
1 & 2 \\
3 & 4
\end{pmatrix}
$$

$$
B = \begin{pmatrix}
5 & 6 \\
7 & 8
\end{pmatrix}
$$