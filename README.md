# TIPE-DATA-VARIABLE-DAN-OPERATOR
Nama: M Irgi Fahrezi

Kelas: TI.21.C5

NIM: 312110430

Matkul: Bahasa Pemrograman

# LAB1
```python
#penggunaan end
print('A', end='')
print('B', end='')
print('C', end='')
print()
print('X')
print('Y')
print('z')

#penggunaan separator
w, x, y, z = 10, 15, 20, 25
print(w, x, y, z)
print(w, x, y, z, sep=',')
print(w, x, y, z, sep='')
print(w, x, y, z, sep=':')
print(w, x, y, z, sep='.....')
````

Penggunaan END Penggunaan end digunakan untuk menambahkan karakter yang dicetak di akhir baris. secara default penggunaan end adalah untuk ganti baris.

```python
print('A', end='')
print('B', end='')
print('C', end='')
```
Penggunaan print () digunakan untuk mencetak output, seperti syntax dibawah ini :
```python
print()
```
Syntax dibawah ini digunakan untuk menampilkan output berupa string
```python
print('X')
print('Y')
print('z')
```
Hasil dari source code tersebut seperti gambar dibawah ini :

![gambar](https://user-images.githubusercontent.com/92860414/139844665-c1770f59-e714-40f0-96ad-d4d6623e634e.png)

Penggunaan separator
Pendeklarasian beberapa variable beserta nilainya
```python
w,x,y,z=10,15,20,25
```
Menampilkan hasil dari variable tiap-tiap variable
```python
print(w,x,y,z)
```
Menampilkan hasil dari tiap-tiap variable dengan menggunakan pemirsah : (koma)
```python
print(w,x,y,z,sep=",")
```
Menampilkan hasil dari tiap-tiap variable dengan menggunakan pemirsah

```python
print(w,x,y,z,sep="")
```
Menampilkan hasil dari tiap-tiap variable dengan menggunakan pemirsah : (titik dua)
```python
print(w,x,y,z,sep=":")
```
Menampilkan hasil dari tiap-tiap variable dengan menggunakan pemirsah -----
```python
print(w,x,y,z,sep="-----")
```
hasil dari syntax / source code diatas adalah seperti berikut ini :

![gambar](https://user-images.githubusercontent.com/92860414/139844989-092f45f9-cbe6-471c-a702-1b9719f66cd1.png)

## Tugas Variable

![gambar](https://user-images.githubusercontent.com/72906579/98073838-c5123100-1e9b-11eb-8f98-b9169d72f107.png)
```python
a=int(input("masukkan nilai a:"))
b=int(input("masukkan nilai b:"))
print("variable a=",a)
print("variable b=",b)
print("hasil penggabungan {1}&{0}=%d".format(a,b) %(a+b))

#konversi nilai variable
a=int(a)
b=int(b)
print("hasil pejumlahan {1}+{0}=%d".format(a,b) %(a+b))
print("hasil pembagian {1}/{0}=%d".format(a,b) %(a/b))
```
Kita akan coba lagi untuk run file tersebut, maka akan muncul seperti gambar dibawah ini :

![gambar](https://user-images.githubusercontent.com/92860414/139845691-6cae666a-c484-46d2-9ae2-3023784157eb.png)

String Format
String formatting atau pemformatan string memungkinan kita menyuntikkan item kedalam string dari pada kita mencoba menggabungkan string menggunakan koma atau string concatenation.
Penggunaan source code yang di berikan oleh dosen seperti berikut :

![gambar](https://user-images.githubusercontent.com/72906579/98077922-ab74e780-1ea3-11eb-9a0f-af6e704ccd67.png)

```python
#string format 1
print(0, 10**0)
print(1, 10**1)
print(2, 10**2)
print(3, 10**3)
print(4, 10**4)
print(5, 10**5)
print(6, 10**5)
print(8, 10**8)
print(9, 10**9)
print(10, 10**10)

#string format 2
print('{0:>3} {1:>16}'.format(0, 10**0))
print('{0:>3} {1:>16}'.format(1, 10**1))
print('{0:>3} {1:>16}'.format(2, 10**2))
print('{0:>3} {1:>16}'.format(3, 10**3))
print('{0:>3} {1:>16}'.format(4, 10**4))
print('{0:>3} {1:>16}'.format(5, 10**5))
print('{0:>3} {1:>16}'.format(6, 10**6))
print('{0:>3} {1:>16}'.format(7, 10**7))
print('{0:>3} {1:>16}'.format(8, 10**8))
print('{0:>3} {1:>16}'.format(9, 10**9))
print('{0:>3} {1:>16}'.format(10, 10**10))
```
String Format 1
Pada syntax / source code strring format satu akan menampilkan output berupa 2 outputan.
Yang pertama (sebelah kiri) akan menampilkan angka urut dari angka 0 hingga 10, sedangkan untuk sebelah kanan akan menampilkan Operasi Aritmatika Pangkat.
Dengan ketentuan sebagai berikut, Operasi pangkat dengan angka kiri sebagai pokok (Rumus : ** [bintang dua] )
Hasil dari syntax tersebut adalah 10 pangkat 0, hingga 10 pangkat 10, dengan output sebagai berikut :

![gambar](https://user-images.githubusercontent.com/92860414/140012781-3ab41463-c486-4c1a-ad5c-673abad11a15.png)

2 * String Format 2*
Pada syntax atau source code string format dua akan menampilkan output berupa 2 output'an juga (seperti String Format 1, yaitu kanan dan kiri )
Dengan ketentuan sebagai berikut :

secara Default, .format() menggunakan rata kiri, angka ke kanan. kita dapat menggunakan opsi opsional <,^, atau > untuk mengatur perataan kiri, tengah, atau kanan. Contoh lain dalam penggunaan .format() sebagai berikut :

Untuk hasil dari String Format 2 adalah :
![gambar](https://user-images.githubusercontent.com/92860414/140013010-e03be1cc-270e-4d49-900b-19a88be9c0fd.png)




## Tugas Latihan
![gambar](https://user-images.githubusercontent.com/92860414/139846060-c8f5bba5-45c8-4560-be83-f5f6e3a7da83.png)

# Flowchart
![gambar](https://user-images.githubusercontent.com/92860414/139847099-e711ad6b-6ed9-4ecb-a321-9d27321c3406.png)

# Program menghitung luas dan keliling lingkaran

![gambar](https://user-images.githubusercontent.com/92860414/139847354-6ae7d855-746a-4fe9-a1b3-051f682c1450.png)

Hasil Output

![gambar](https://user-images.githubusercontent.com/92860414/139848894-6ecd24c9-ebf6-427a-8b02-70fa239417ea.png)

untuk mengambil 2 angka pecahan saja kita pakai fungsi format() seperti berikut:

![gambar](https://user-images.githubusercontent.com/92860414/139849197-31e6c23d-cd3f-4ef0-8045-6bc7d9b85d2c.png)

Dengan penggunaan fungsi format(luas,’.2f’) akan menghasilkan 2 angka pecahan saja.
# Tipe-Data-Variable-dan-Operator
