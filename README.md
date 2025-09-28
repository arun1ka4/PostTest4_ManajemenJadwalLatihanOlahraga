# Manajemen Jadwal Latihan Olahraga


Nama  : Nayla Lelyanggraheni Hutomo

NIM   : 2409116061


# Deskripsi Program
Program manajemen jadwal latihan olahraga adalah program berbasis Java yang digunakan user untuk mengatur jadwal latihan olahraga mingguan.
Fitur program ini terdiri dari beberapa package:
1. Model: Memiliki class JadwalLatihan dengan 2 subclass dan 1 interface
- class Kardio: terdapat tambahan data tambahan yaitu jarak (dalam satuan km) dan durasi (dalam satuan menit)
- class Kekuatan terdapat tambahan data tambahan yaitu set dan repetisi
- Interface EvalLatihan berisi method evaluasi
3. Service: Menangani logika bisnis dan logika CRUD yang terdiri dari
- Tambah jadwal -> Menambahkan jenis latihan serta hari latihan tersebut
- Lihat jadwal -> Melihat jadwal latihan yang telah ditambahkan
- Update jadwal -> Mengganti jenis latihan dan hari latihan sesuai nomor jadwal
- Hapus jadwal -> Menghapus jadwal latihan yang ada sesuai nomor jadwal
- Cari berdasarkan hari -> Mencari jadwal latihan berdasarkan hari
- Keluar dari program -> Program berhenti
3. Main: Berfungsi sebagai entry poin program

# Dokumentasi Program

## 1. Subclass Kardio

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/295b5bfc-8d45-48f9-8c79-492648a30e0c" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/f3a3c169-4991-42a3-a5e9-0a38dfdeb451" />

Beberapa jadwal latihan menampilkan hasil evaluasi berdasarkan durasi atau jarak latihan, sehingga setiap jadwal memberikan saran atau feedback yang berbeda-beda. Ada juga jadwal latihan yang tidak menampilkan evaluasi sama sekali. Hal ini terjadi karena penggunaan INTERFACE dalam program.
- Jika sebuah jadwal latihan tidak mengimplementasikan interface atau tidak memenuhi kondisi dalam method evaluasi, maka evaluasi tidak akan muncul pada output.
- Dengan cara ini, interface memastikan bahwa hanya jadwal yang sesuai yang memberikan feedback, sementara jadwal lain tetap dapat ditampilkan tanpa evaluasi.

Selain itu, terdapat jadwal latihan yang menampilkan salah satunya input dari durasi atau jarak tempuh latihan. Ini disebabkan penggunaan OVERLOADING. Hal ini disebabkan salah satu dari variabel tersebut diinput nilai 0.

## 2. Subclass Kekuatan

<img width="707" height="592" alt="image" src="https://github.com/user-attachments/assets/a5d0d2c6-a6f8-4c75-8e68-5d6abfb6383d" />

Pada subclass Kekuatan, saya menggunakan INTERFACE tapi programnya juga sama. Jika Set dan Repetisi bernilai 0, maka hal ini tidak sesuai dengan kondisi memenuhi penggunaan interface yaitu adanya evaluasi yang ditampilkan. 

## 3. Tanpa memilih kategori == tidak melanjutkan program ke Subclass manapun

<img width="374" height="639" alt="image" src="https://github.com/user-attachments/assets/adcbf77e-f6fd-4b73-a607-297b0961ddef" />

Perbedaan penggunaan OVERRIDING dan tidak memakai dapat terlihat di sini. Jika user tidak memilih kategori, objek hanya berupa JadwalLatihan biasa, sehingga yang ditampilkan hanyalah informasi dasar dari superclass. Sedangkan jika user memilih kategori seperti Kardio atau Kekuatan, objek menjadi subclass yang menimpa method tampilkanInfo() dan evaluasi(). Akibatnya, output menampilkan informasi dasar plus informasi spesifik kategori dan evaluasi latihan.
