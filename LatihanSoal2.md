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
double Penjumlahan(double x, double y) {
  return x + y;
}
```

d. 
```c++
class Employee {
  private:
    int salary;

  public:
    void setSalary(int s) {
      salary = s;
    }
    int getSalary() {
      return salary;
    }
};
```
e. 
```c++
int main() {
  Car myCar;
  myCar.honk();
  cout << myCar.brand + " " + myCar.model;
  return 0;
}
```
f. 
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

class Mobil : public Vehicle {

};

int main()
{   
    Mobil obj;
    return 0;
}
```

b.
```c++
#include <iostream>
using namespace std;

class Kendaraan {
public:
    void kendaraan() { 
        cout << "Ini adalah Kendaraan\n"; }
};

class Mobil : public Kendaraan {
};

class Bus : public Kendaraan {
};

int main()
{
    Mobil obj1;
    Bus obj2;
    return 0;
}
```

c.
```c++
#include <iostream>
using namespace std;

class Animal {
public:
void speak() {
cout << "Hewan bersuara" << endl;}
};

class Dog : public Animal {
public:
void speak() {
cout << "Anjing menggonggong" << endl;}
};

int main() {
Animal animal;
Dog dog;
animal.speak();
dog.speak();

return 0;
}
```
3. Buatlah program berikut: \
a. Buatlah sebuah kelas `Mahasiswa` yang memiliki atribut `nama`, `NIM`, dan `jurusan`. Implementasikan constructor untuk menginisialisasi atribut tersebut, dan buatlah method `tampilkanInfo()` untuk menampilkan informasi mahasiswa. \
<br>
b. Buatlah kelas `Dosen` yang mewarisi dari kelas `Person`. Kelas `Person` memiliki atribut `nama` dan `usia`. Kelas `Dosen` memiliki atribut tambahan `NIP` dan `mataKuliah`. Buat constructor, method untuk menampilkan informasi, serta method untuk mengajar (`mengajar()`). \
c. Buatlah kelas `Buku` yang memiliki atribut `judul`, `author`, `isbn` dan `tahunterbit`. Implementasikan constructor untuk menginisialisasi atribut tersebut, dan buatlah method `displayInfoBuku()` untuk menampilkan informasi mahasiswa. 

4. Berikan penjelasan mengenai\
a. Perbedaan `struct` dan `class` \
b. object oriented programming \
c. public, private, dan protected \
d. Enkapsulasi \
e. Inheritance

