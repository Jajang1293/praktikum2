# praktikum2

## latihan1.cpp : progam menghitung biangan terbesar dari 3 bilangan

**Alur algoritma**
1. Mendeklarasikan variable `int A, B, C` sebagai variable input.
2. Membaca input dari keyboard `cin >> A >> B >> C`
3. Membandingkan nilai variable **A** dan **B**
4. Kondisi **True**, maka bandingkan nilai variable **A** dengan **C**
5. Kondisi **False**, maka bandingkan nilai variable **B** dengan **C**

**Flowchart Prgram** 
![Flowchart](https://raw.githubusercontent.com/abuazzam/praktikum2/master/flowchart.png)

**code program lengkap:**
```c++
#include<iostream>

using namespace std;

int main() {
    int A, B, C;
    
    cout << "Masukkan bilang 1: "; 
    cin >> A;
    
    cout << "Masukkan bilang 2: "; 
    cin >> B;
    
    cout << "Masukkan bilang 3: "; 
    cin >> C;
    
    if (A > B) {
        if (A > C) 
            cout << "Bilangan terbesar adalah: " << A << endl;
        else 
            cout << "Bilangan terbesar adalah: " << C << endl;
    } else {
        if (B > C) 
            cout << "Bilangan terbesar adalah: " << B << endl;
        else 
            cout << "Bilangan terbesar adalah: " << C << endl;
    } 
}
```

hasilnya:
![img](https://raw.githubusercontent.com/abuazzam/praktikum2/master/hasil.png)

