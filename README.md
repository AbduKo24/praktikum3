# praktikum3
# 1.Program Mencari Bilangan Terbesar dari 3 Variabel
Program sederhana untuk menentukan bilangan terbesar dari tiga angka yang diinput
# 1.1 Deskripsi Program
Program ini akan:
. Meminta user memasukan 3 bilangan berbeda
. Membandingan ketiga bilangan tersebut
. Menentukan bilangan mana yang terbesar
. Menampilkan hasilnya ke layar

# 2. Program Mencari Bilangan Terbesar
Program sederhana untuk mencari nilai terbesar dari sekumpulan bilangan yang dimasukkan oleh pengguna menggunakan loop while True dan break statement.

# 2.1 Deskripsi Program
Program ini dibuat menggunakan bahasa Python dengan fitur:

*Menggunakan while True untuk perulangan tak terbatas

*Menggunakan break statement untuk menghentikan program

*Membandingkan setiap input dengan nilai maksimum yang tersimpan

*Menampilkan bilangan terbesar yang ditemukan

## Flowchart 1
![Flowchart](flowchart1.png)

## Output 1
```
Masukkan bilangan A: 6
Masukkan bilangan B: 8
Masukkan bilangan C: 3
Terbesar adalah B
Bilangan terbesar adalah: 8
```



## Flowchart 2
![Flowchart](FLowchart2.png)

## Output 2
```
masukan bilangan :7
masukan bilangan:8
masukan bilangan:9
masukan bilangan:57
masukan bilangan:84
masukan bilangan:9
masukan bilangan:0
bilangan terbesar = 0
```
# Cara Kerja Program 1
Program ini dimulai dengan meminta pengguna untuk memasukkan tiga angka. Setelah angka-angka tersebut dimasukkan, program menggunakan fungsi max() untuk menentukan angka yang paling besar di antara ketiga angka tersebut. Fungsi max() secara otomatis membandingkan semua angka dan mengembalikan yang terbesar. Setelah menemukan angka terbesar, program menampilkan hasilnya kepada pengguna dengan kalimat yang jelas. Dengan cara ini, kode menjadi lebih ringkas dan mudah dibaca, tanpa perlu membuat banyak kondisi untuk perbandingan. melakukan pengecekan dengan urutan :

*Apakah A > B?
*Jika ya: cek apakah A > C?
*Jika ya: A adalah terbesar
*Jika tidak: C adalah terbesar
*Jika tidak: cek apakah B > C?
*Jika ya: B adalah terbesar
*Jika tidak: C adalah nilai terbesar
# Cara Kerja Program 2
variable max di isi dengan nilai 0, setelah itu terdapat variable inputan dengan nama bilangan, jika kondisi bilangan tidak sama dengan 0 maka cari bilangan lebih dari max dan variable max di set dengan bilangan tersebut. Jika bilangan lebih kecil dari max maka bilangan input kembali sehingga akan menghasilkan bilangan terbesar dari operasi tersebut.
