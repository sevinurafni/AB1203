## Structure

Structure dalam bahasa pemrograman C++ adalah cara untuk mengelompokkan beberapa variabel yang berbeda, tetapi terkait menjadi satu unit. Ini memungkinkan Anda untuk membuat tipe data yang terdiri dari beberapa anggota dengan tipe data yang berbeda.

## Keuntungan Penggunaan Struktur

- Organisasi Data: Struktur memungkinkan Anda untuk mengelompokkan data yang terkait bersama.
- Keterbacaan: Penggunaan struktur dapat membuat kode lebih mudah dibaca karena menggambarkan hubungan antara data.
- Kemudahan Penggunaan: Struktur memungkinkan Anda untuk membuat tipe data yang sesuai dengan kebutuhan aplikasi Anda.

### Mendefinisikan Struktur

Anda dapat mendefinisikan sebuah struktur dengan menggunakan kata kunci struct diikuti dengan nama struktur dan di dalamnya mendefinisikan anggota-anggota struktur tersebut.

```C++
// Definisi Struktur
struct Mahasiswa {
    int nomorInduk;
    char nama[50];
    int umur;
    float IPK;
};
```

### Mengakses Anggota Struktur
Setelah mendefinisikan struktur, kita dapat membuat variabel dari tipe struktur tersebut dan mengakses anggota-anggotanya menggunakan operator titik (.).

```C++
Mahasiswa mhs1; // Mendeklarasikan variabel mhs1 bertipe Mahasiswa

// Mengakses dan menginisialisasi anggota-anggota struktur
mhs1.nomorInduk = 12345;
strcpy(mhs1.nama, "Sevi Nurafni");
mhs1.umur = 20;
mhs1.IPK = 3.75;
```

### Menampilkan Informasi Anggota Structure
```C++
// Menampilkan informasi mahasiswa
    cout << "Nomor Induk: " << mhs1.nomorInduk << endl;
    cout << "Nama: " << mhs1.nama << endl;
    cout << "Umur: " << mhs1.umur << endl;
    cout << "IPK: " << mhs1.IPK << endl;
```
output:
```yml
Nomor Induk: 12345
Nama: Sevi Nurafni
Umur: 20
IPK: 3.75
```

## Tugas
Modelkan beberapa entitas data yang berkaitan dengan industri pertanian menggunakan struktur (struct) dalam bahasa pemrograman C++. Anda akan membuat struktur untuk menyimpan informasi tentang tanaman, hewan, dan petani.

Instruksi Tugas
1. Buatlah sebuah program C++ yang mendefinisikan tiga struktur: `Tanaman`, `Hewan`, dan `Petani`.
2. Setiap struktur harus memiliki setidaknya tiga anggota data yang relevan dengan entitas yang mewakilinya. Contoh, struktur Tanaman bisa memiliki anggota data seperti `nama`, `harga`, dan 'jumlahPanenTahunan'.
3. Implementasikan fungsi untuk memasukkan informasi ke dalam struktur (input).
4. Implementasikan fungsi untuk menampilkan informasi dari struktur (output).
5. Buatlah beberapa contoh data untuk setiap struktur yang Anda buat, dan gunakan fungsi untuk menampilkan data tersebut.

Contoh Output
```
Informasi Tanaman:
Nama: Jagung
Harga per Kilogram: $0.50
Jumlah Panen Tahunan: 5000 kg

Informasi Hewan:
Nama: Sapi
Jumlah: 50 ekor
Harga per Ekor: $1000

Informasi Petani:
Nama: Budi
Usia: 35 tahun
Pendapatan Tahunan: $30000
```
