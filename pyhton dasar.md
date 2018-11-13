# **Python Dasar**
![Python Logo](python.png)
## Mencetak tulisan I Love You So Much

```python
print("I Love You So Much")
```
Syntax yang sangat sederhana untuk mencetak kalimat ke layar komputer

## Membuat data input via keybord
```python
x = input ('masukan kalimat: ')
print (x)
```

terdapat variabel `x` yang memiliki kata kunci `input`

kemudian terdapat syntax `('masukan nama : ')` yang nantinya akan menampilkan masukan nama :

kemudian `print (x)` yang akan mencetak nilai `x`, yang dimana nilainya sudah kita input sebelumnya

## Perulangan
```python
ulang = 10
for ulang in x :
    print ("Inilah yang ingin ku katakan  "+x)
```

Script di atas merupakan bentuk perulangan menggunkan for.

Terdapat konstanta `ulang` dengan nilai 10, kemudian `for ulang in x :` yang berarti nilai yang disimpan pada variabel `x` diulang sebanyak nilai yang tersimpan pada `ulang` yaitu 10.

`print("Inilah yang ingin ku katakan  "+x)` script ini akan menampilkan nilai yang tersimpan pada variabel `x`.

## Masukan Dengan Bentuk Array
```python
n = int (input ("masukan nilai : "))
arr = []
for _ in range (n):
    x = str (input("masukan kalimat : "))
    arr.append(x)
```

Variabel array pada pyhton dideklarasikan dengan bentuk `arr = []`.
Pada contoh yang saya berikan mula - mula saya mendeklarasikan inputan dengan variabel `n` dengan tipe data `int` yang nantinya bagian ini akan menerima jumlah array yang akan disimpan.

`for _ in range (n):` perulangan untuk mengisi array dengan batas yang sudah ditentukan sebelumnya.
`x = str (input("masukan kalimat : "))` script tersebut yang berfungsi menangkap inputan dan disimpan pada variabel `x` dengan tipe data `str` yang berarti string. 
`arr.append(x)` berfungsi untuk memasukan setiap data ke dalam array dengan variabel `arr`

**untuk contoh code dan hasil otuput bisa dilihat pada file dengan nama syntax basic**
