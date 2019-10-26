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
for n in range (ulang) :
    print (n)
```

Script di atas merupakan bentuk perulangan menggunkan for.

Terdapat konstanta `ulang` dengan nilai 10, kemudian `for n in range (ulang) :` yang berarti nilai yang disimpan pada variabel `n` diulang sebanyak nilai yang tersimpan pada `ulang` yaitu 10.

`print(n)` script ini akan menampilkan nilai yang tersimpan pada variabel `n` dalam hal ini `n` memiliki nilai awal `0` karena variabel yang ada pada perulangan dihitung dari `0`.

## List
```python
listA = ['teks 1', 'teks 2', 1999, 2000]
```
List juga bisa dibilang sebagai kumpulan data pada satu variabel, dari contoh di atas data disimpan pada satu variabel bernama `listA`. List dideklarasikan dengan tanda `[ ]`.

## Tuple
```python
ctuples = (1,2,3,4,5)
```
Tuple hampir sama dengan List dari segi simbol yang membedakan adalah tanda kurung `( )` untuk menampung data dalam variabel. Selain itu tuple tidak dapat diedit setelah dideklarasikan.

## Dictionary
```python
cdict = {'Nama': 'Zahra', 'Umur': 21, 'Posisi': 'Back End'}
```
Dictionary mengenal `key` dan `value` dapat dideklarasikan seperti contoh di atas.

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

**untuk contoh code dan hasil otuput bisa dilihat pada file dengan nama Beginer's**
