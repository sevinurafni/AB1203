1. Jelaskan maksud instruksi-instruksi dalam bahasa C++ di bawah ini. Instruksi ini bisa muncul di bagian mana pun dari suatu program. \
a. 
```c++
class Circle {
  private: 
    double radius;

  public:
    double calculateArea() {
      return PI * pow(radius, 2); 
    }

    double calculateCircumference() {
      return 2 * PI * radius;
    }
};
```
b.
```c++
class Car {        
  public:          
    string brand;  
    string model;  
    int year;      
    Car(string x, string y, int z) {
      brand = x;
      model = y;
      year = z;
    }
};
```
c. 
```c++
class Student : private Person {
    char course[50];
    int fee;
```

2. Tuliskan keluaran (apa yang tercetak di layar) dari program-program di bawah ini. Jika tidak ada keluaran, tuliskan: Tidak ada keluaran. Program-program di bawah ini sudah dipastikan lolos kompilasi. \
a. 
```c++
#include<iostream>
using namespace std;

class Kendaraan {
  public:
    void kendaraan()
    {
      cout << "Ini adalah kendaraan bermotor\n";
    }
};

class Mobil : public Kendaraan {

};

int main()
{   
    Mobil obj;
    return 0;
}
```

3. Buatlah program berikut: \
Buatlah kelas `Buku` yang memiliki atribut `judul`, `author`, `isbn` dan `tahunterbit`. Implementasikan constructor untuk menginisialisasi atribut tersebut, dan buatlah method `displayInfoBuku()` untuk menampilkan informasi mahasiswa. 

4. Lengkapi program berikut \
a. Buat sebuah objek dari `MyClass` bernama `myObj`. \
`...`  `...`; \
b. Gunakan penentu akses untuk membuat anggota `MyClass` dapat diakses dari luar kelas. \
```
class MyClass {
  ...:
    int myNum;
};
```
c. Buat objek `MyClass` bernama `myObj`, dan gunakan untuk mengatur nilai `myNum` menjadi `15`. \
```
class MyClass {
  public:
    int myNum;
};

int main() {
  ... ...;
  ...(.)... ...  ...;
  cout << myObj.myNum; 
  return 0;
}
```
