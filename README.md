# Biodata
Nama: ANDREAN PUTRA ARYA

Kelas: TI.24.A4

NIM: 312410341

Matkul: Bahasa Pemrograman

# Latihan1.py

```python
import random

n = int(input("Masukkan nilai N: "))

for i in range(1, n+1):
  angka_acak = random.random()
  print(f"data ke: {i} => {angka_acak}")

print("Selesai")
```

kkkk

```python
import random
```
Baris ini mengimpor modul random, yang berisi fungsi-fungsi untuk menghasilkan angka acak.

```python
n = int(input("Masukkan nilai N: "))
```
Pengguna meminta untuk memasukkan nilai integer `n` yang menentukan berapa banyak angka acak yang akan dihasilkan. Fungsi `input()` menerima masukan dari pengguna dalam bentuk string, dan `int()` mengonversinya menjadi integer.

```python
for i in range(1, n + 1):
```
`for` adalah perulangan yang akan berjalan sebanyak N kali, `range(1, n + 1)` menghasilkan urutan angka mulai dari 1 hingga `N` (termasuk `N`), yang digunakan untuk menentukan jumlah angka acak yang akan dihasilkan.

```python
  angka_acak = random.random()
  print(f"data ke: {i} => {angka_acak}")
```
Di dalam perulangan, `random.random()` digunakan untuk menghasilkan angka acak dalam rentang 0.0 hingga 1.0, dengan nomor urut datanya (`data ke: {i}`). Format `{i}` dan `{angka_acak}` digunakan dalam `f-string` untuk menampilkan nilai variabel `i` dan `angka_acak` secara langsung di dalam string.

```python
print("Selesai")
```
Setelah perulangan selesai, baris ini menampilkan pesan `"Selesai"` untuk menandakan bahwa program telah selesai menjalankan seluruh instruksi.

