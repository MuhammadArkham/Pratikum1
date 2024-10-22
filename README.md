# Praktikum3

Muhammad Arkhamullah Rifai Asshidiq

Bahasa pemrograman

312410545

# code program
```python
max_number = int(0)

while True:
    number = int(input("Masukan bilangan (input 0 untuk berhenti): "))

    if number == 0:
        break

    if number > max_number:
        max_number = number

print("Bilangan terbesar: ", max_number)

```
# Eksekusi program
![Foto](https://github.com/MuhammadArkham/Foto/blob/main/Screenshot%202024-10-22%20211528.png?raw=true)

# Penjelasan program

```Python
max_number = int(0)
```

Ini adalah inisialisasi variabel max_number dengan nilai awal 0
Berfungsi untuk menyimpan bilangan terbesar yang ditemukan

```Python
while True:
```

Ini adalah loop tak terbatas (infinite loop)
Akan terus berjalan sampai dihentikan dengan perintah break
Berfungsi untuk terus meminta input dari user

```Python
number = int(input("Masukan bilangan (input 0 untuk berhenti): "))
```

Meminta input dari user dalam bentuk string
Mengkonversi input tersebut menjadi bilangan bulat (integer)
Menyimpan hasilnya dalam variabel number

```Python
if number == 0:
```

Mengecek apakah bilangan yang dimasukkan adalah 0
Jika ya, maka break akan menghentikan loop
Ini adalah kondisi untuk keluar dari program

```Python
if number > max_number:
```

Membandingkan bilangan yang baru diinput dengan nilai maksimum yang tersimpan
Jika bilangan baru lebih besar, maka akan masuk ke baris berikutnya

```Python
max_number = number
```

Memperbarui nilai max_number dengan bilangan yang lebih besar yang baru ditemukan
Berfungsi untuk selalu menyimpan bilangan terbesar

```Python
print("Bilangan terbesar: ", max_number)
```

Menampilkan bilangan terbesar yang ditemukan setelah loop selesai

