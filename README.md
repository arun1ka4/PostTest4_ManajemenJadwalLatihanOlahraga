# Manajemen Jadwal Latihan Olahraga


# Deskripsi Program
Program manajemen jadwal latihan olahraga adalah program berbasis Java yang digunakan user untuk mengatur jadwal latihan olahraga mingguan.
Fitur program ini terdiri dari beberapa package:
1. Model: Memiliki class JadwalLatihan dengan subclassnya yaitu class Kardio dan Kekuatan
- class Kardio: terdapat tambahan data tambahan yaitu jarak (dalam satuan km) dan durasi (dalam satuan menit)
- class Kekuatan terdapat tambahan data tambahan yaitu set dan repetisi
3. Service: Menangani logika bisnis dan logika CRUD yang terdiri dari
- Tambah jadwal -> Menambahkan jenis latihan serta hari latihan tersebut
- Lihat jadwal -> Melihat jadwal latihan yang telah ditambahkan
- Update jadwal -> Mengganti jenis latihan dan hari latihan sesuai nomor jadwal
- Hapus jadwal -> Menghapus jadwal latihan yang ada sesuai nomor jadwal
- Cari berdasarkan hari -> Mencari jadwal latihan berdasarkan hari
- Keluar dari program -> Program berhenti
3. Main: Berfungsi sebagai entry poin program

# Dokumentasi Program
1. Pilih Opsi Nomor 1

Subclass Kardio 

<img width="368" height="442" alt="image" src="https://github.com/user-attachments/assets/d5c07b2d-0800-4ef7-9165-44a4a52f2126" />

Jika input durasi atau jarak != angka

<img width="418" height="257" alt="image" src="https://github.com/user-attachments/assets/8d9e9c27-72fd-4e28-83db-3146111abc6a" />

Subclass Kekuatan

<img width="402" height="440" alt="image" src="https://github.com/user-attachments/assets/a8100073-58f6-4ca4-8b6a-6b0b79ab50f5" />

Jika input set dan repetisi != angka bilangan bulat

<img width="407" height="248" alt="image" src="https://github.com/user-attachments/assets/a90bee44-b7bb-4118-87e2-0cef0412a710" />

3. Pilih Opsi Nomor 2

Jika ada jadwal latihan yang pernah ditambahkan

<img width="383" height="552" alt="image" src="https://github.com/user-attachments/assets/18174a11-3dc3-41e4-9530-0a90c5ea602f" />

Jika tidak ada jadwal yang ditambahkan

<img width="338" height="216" alt="image" src="https://github.com/user-attachments/assets/cbe7bbbf-3e1a-49cc-ab30-644f5fa93fb8" />

4. Pilih Opsi Nomor 3

Jika ada jadwal latihan yang pernah ditambahkan

<img width="502" height="668" alt="image" src="https://github.com/user-attachments/assets/6f8dc7c8-0894-4076-bdde-485ece2edd66" />

Jika tidak ada jadwal yang ditambahkan

<img width="377" height="228" alt="image" src="https://github.com/user-attachments/assets/b8858a60-d83b-4dcf-b6b1-51d83d2173b6" />

6. Pilih Opsi Nomor 4

Jika ada jadwal latihan yang pernah ditambahkan

<img width="459" height="448" alt="image" src="https://github.com/user-attachments/assets/8ce82f8f-dfbc-42dd-94f2-0596367710d8" />

Jika nomor yang diketik tidak sesuai dengan pilihan yang ada

<img width="472" height="438" alt="image" src="https://github.com/user-attachments/assets/0af2d70a-59fc-4be0-91e2-393b196453b8" />

Jika tidak ada jadwal yang ditambahkan

<img width="342" height="217" alt="image" src="https://github.com/user-attachments/assets/e987bb75-f8a4-446e-8676-f465e176094f" />

8. Pilih Opsi Nomor 5

Jika ada nama hari yang dicari

<img width="431" height="349" alt="image" src="https://github.com/user-attachments/assets/a0bca316-b69c-4332-88e4-62b8fcaf91a4" />

Jika tidak ada nama hari yang dicari

<img width="409" height="247" alt="image" src="https://github.com/user-attachments/assets/82b78310-15fe-4506-bda8-f91e4329057f" />

Jika tidak ada jadwal yang ditambahkan

<img width="424" height="241" alt="image" src="https://github.com/user-attachments/assets/b373b556-1ca8-4752-978a-c3fc0d4dcae4" />

10. Pilih Opsi Nomor 6

<img width="403" height="226" alt="image" src="https://github.com/user-attachments/assets/0212f219-4dee-428e-8da4-81e518ee1f1a" />
