1. Buatlah sebuah program yang menerima suhu air (dalam derajat celcius) dan menuliskan wujud air ke layar sebagai berikut:
- Jika suhu air <= 0 derajat, maka tuliskan “beku”
- Jika suhu air > 0 dan kurang dari 100 derajat, maka tuliskan “cair”
- Jika suhu air >= 100, maka tuliskan “uap”

2. Buatlah fungsi IsVokal yang
- mempunyaiparameterinputsebuahcharacterhuruf
kecil ‘a’ s.d. ‘z’
- menghasilkantruejikacharactertersebutadalah vokal (‘a’, ‘i’, ‘u’, ‘e’, ‘o’)

3.Tuliskan keluaran program berikut ini:
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

4. Tuliskan keluaran (apa yang tercetak di layar) dari program di bawah ini jika N = 8 pada kotak kosong di samping kanan program. Semua komentar program sengaja dihilangkan. Program sudah dipastikan lolos kompilasi.
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