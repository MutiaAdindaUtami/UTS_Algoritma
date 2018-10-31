# UTS_Algoritma


**Soal Pertama**

**Alur Program**

1. Deklarasikan variabel A, B, X, Y sebagai variabel input.
2. Membaca input keyboard cin >> A >> B >> X >> Y.
3. Membandingkan variabel X dengan Y jika sama.
4. Karena statement FALSE tidak akan terjadi {X != Y}
5. Dan jika statement TRUE maka X < Y berlaku rumus statement TRUE dengan Syntax X = X + A
6. Dan jika statement FALSE Y = Y + B.
7. Maka akan muncul X = X + A = (hasilnya).

**Code Program**

```c++

#include<iostream>

using namespace std;

int main ()
{

	int A,B,X,Y;
    
	cout << "Masukkan bilangan 1: ";
	cin >> A;
	cout << "Masukkan bilangan 2: ";
	cin >> B;

   	X = A;
    	Y = B;
	if (X  != Y )
              {if  ( X < Y )
                   { X = X + A; }
               else
                   	   { Y = Y + B; }
    		   }


	cout << X;




     }



**Soal Kedua**

**Alur Program**

1. Deklarasikan variabel input `N, X, T, Batas;` sebagai inputnya
2. Memasukkan nilai **N** yaitu 2 angka terakhir NIM saya, maka N adalah 87 dan batasnya adalah 227 dari hasil jumlahan N + 140.
3. Masukkan variabel **X** , dan **T** , **X** nya adalah 20 dan kemudian T adalah 87 (dari N).
4. Dimana T kurang dari sama dengan batas, berarti tidak boleh melebihi batas.
5. Kemudian menghitung `X = X + 10;` , dan hasilnya 30 kemudian menghitung `T = T + X;` , hasilnya adalah 227.
6. Kemudian cetak variabel T

**code Program**

```c++

#include<iostream>
using namespace std;
int main ()

{ int N,X,T,Batas;
    N = 87;
    Batas = N + 100;
    X = 20;
    T = N;
while ( T <= Batas)
        {T = T + X;
        X = X + 10;
        }
    cout << T;

 }
 