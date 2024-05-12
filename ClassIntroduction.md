## Pengantar Pemrograman Berorientasi Objek (OOP)

Pemrograman Berorientasi Objek (OOP) adalah paradigma pemrograman yang menggunakan "objek" untuk memodelkan data dan perilaku yang terkait bersama. Dalam OOP, objek adalah representasi konkret dari suatu konsep di dunia nyata atau sistem yang sedang dibangun.

### Komponen-komponen Utama OOP:
1. Kelas (Class): Kelas adalah cetak biru untuk objek. Ini mendefinisikan atribut dan metode yang akan dimiliki oleh objek. Objek dibuat dari kelas, dan setiap objek merupakan contoh (instance) dari kelas tersebut.
```c++
#include <iostream>
using namespace std;

// Deklarasi kelas
class Manusia {
public:
    string nama;
    int umur;
};
```

2. Objek (Object): Objek adalah instansi dari sebuah kelas. Ini merupakan entitas yang memiliki atribut dan perilaku tertentu.
```c++
#include <iostream>
using namespace std;

// Deklarasi kelas
class Manusia {
public:
    string nama;
    int umur;
};

int main() {
    // Membuat objek dari kelas Manusia
    Manusia orang;

    // Mengakses atribut objek dan memberi nilainya
    orang.nama = "John";
    orang.umur = 30;

    // Menampilkan informasi objek
    cout << "Nama: " << orang.nama << endl;
    cout << "Umur: " << orang.umur << endl;

    return 0;
}
```

3. Atribut (Attribute): Atribut adalah data yang terkait dengan sebuah kelas atau objek. Misalnya, sebuah objek "Mobil" bisa memiliki atribut seperti "warna", "kecepatan", dan "bahan bakar".
```c++
#include <iostream>
using namespace std;

// Deklarasi kelas
class Manusia {
public:
    string nama; // Attribute 1
    int umur;    // Attribute 2
};

int main() {
    // Membuat objek dari kelas Manusia
    Manusia orang;

    // Mengakses atribut objek dan memberi nilainya
    orang.nama = "John";
    orang.umur = 30;

    // Menampilkan informasi objek
    cout << "Nama: " << orang.nama << endl;
    cout << "Umur: " << orang.umur << endl;

    return 0;
}
```

4. Metode (Method): Metode adalah fungsi atau perilaku yang terkait dengan sebuah kelas. Mereka digunakan untuk melakukan tindakan tertentu pada objek.
```c++
#include <iostream>
using namespace std;

// Deklarasi kelas
class Manusia {
public:
    string nama;
    int umur;

    // Metode untuk menampilkan informasi
    void tampilkan_info() {
        cout << "Nama: " << nama << endl;
        cout << "Umur: " << umur << endl;
    }
};

int main() {
    // Membuat objek dari kelas Manusia
    Manusia orang;

    // Memberi nilai atribut objek
    orang.nama = "John";
    orang.umur = 30;

    // Memanggil metode untuk menampilkan informasi
    orang.tampilkan_info();

    return 0;
}
```

### Prinsip-prinsip Utama OOP:
1. Enkapsulasi: Ini adalah konsep membatasi akses langsung ke beberapa komponen dalam objek dan menyembunyikan detail implementasi. Dengan enkapsulasi, objek hanya berkomunikasi melalui antarmuka yang didefinisikan dengan jelas.

2. Pewarisan (Inheritance): Pewarisan memungkinkan kelas baru untuk mewarisi perilaku (metode) dan karakteristik (atribut) dari kelas yang sudah ada. Hal ini memungkinkan penggunaan kembali kode dan pembuatan hierarki kelas.

3. Polimorfisme: Polimorfisme memungkinkan objek dari kelas yang berbeda untuk merespons dengan cara yang berbeda terhadap pemanggilan metode yang sama. Ada polimorfisme statis dan dinamis.

4. Abstraksi: Abstraksi adalah konsep memfokuskan pada fitur yang penting sambil menyembunyikan detail yang tidak penting. Ini membantu dalam menyederhanakan kompleksitas sistem.