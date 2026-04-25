# SiLapor-campus
Aplikasi pelaporan fasilitas kampus berbasis web
# Aplikasi Lapor Campus

## Deskripsi Aplikasi

Aplikasi Lapor Campus adalah sistem pelaporan kerusakan fasilitas kampus berbasis web yang memungkinkan mahasiswa atau pengguna untuk melaporkan kerusakan fasilitas seperti lampu, AC, kursi, kebersihan, dan lainnya. 

Aplikasi ini menyediakan dua peran pengguna, yaitu pelapor dan admin. Pelapor dapat mengirim laporan kerusakan, sedangkan admin dapat melihat laporan yang masuk dan mengubah status laporan menjadi Menunggu, Diproses, atau Selesai.

---

## Fitur Utama

1. Login sebagai Admin
2. Login sebagai Pelapor
3. Mengirim laporan kerusakan fasilitas
4. Memilih jenis laporan dari dropdown
5. Melihat daftar laporan
6. Admin dapat mengubah status laporan
7. Validasi input form

---

## Link Aplikasi

Link Github (Source Code):
https://github.com/najwaizzah/SiLapor-campus

Link Publish Web:
https://najwaizzah.github.io/SiLapor-campus/

-----

## Skenario Pengujian Aplikasi

Pengujian dilakukan untuk memastikan bahwa aplikasi berjalan dengan baik sesuai dengan aspek kualitas perangkat lunak yang telah dirancang pada Daily Project 6.

| No | Aspek Kualitas | Fitur yang Diuji       | Skenario Pengujian                                 | Hasil yang Diharapkan | Hasil |
|----|----------------|----------------------- |----------------------------------------------------|----------------------|------|
| 1  | Functionality  | Login Admin            | Masukkan username admin dan password admin         | Sistem menampilkan dashboard admin | Berhasil |
| 2  | Functionality  | Login Pelapor          | Masukkan email dan password pelapor                | Sistem menampilkan dashboard pelapor | Berhasil |
| 3  | Functionality  | Kirim Laporan          | Pelapor mengisi nama, jenis laporan, dan deskripsi | Laporan tersimpan dalam sistem | Berhasil |
| 4  | Functionality  | Tampilkan Laporan      | Admin membuka dashboard admin | Data laporan ditampilkan dalam tabel | Berhasil |
| 5  | Functionality  | Ubah Status Laporan    | Admin mengubah status laporan menjadi Diproses | Status laporan berubah sesuai pilihan | Berhasil |
| 6  | Usability      | Antarmuka Pengguna     | Pengguna membuka aplikasi | Tampilan mudah dipahami dan digunakan | Berhasil |
| 7  | Reliability    | Penyimpanan Data       | Pelapor mengirim laporan | Data laporan tersimpan di sistem | Berhasil |
| 8  | Efficiency     | Waktu Respon           | Pengguna melakukan login | Sistem merespon dengan cepat | Berhasil |
| 9  | Functionality  | Dropdown Jenis Laporan | Pelapor memilih jenis laporan | Sistem menampilkan pilihan kategori laporan | Berhasil |
| 10 | Reliability    | Validasi Form          | Pelapor tidak mengisi field | Sistem menampilkan pesan error | Berhasil |

---

## Cara Menjalankan Aplikasi

1. Buka file index.html menggunakan browser
2. Login sebagai pelapor untuk mengirim laporan
3. Login sebagai admin untuk mengelola laporan

Login Admin:

Username: admin  
Password: admin

Login Pelapor:

Email: bebas  
Password: bebas
