# LAPORAN PRAKTIKUM 5

# CODE PROGRAM DAFTAR NILAI

## Step 1 : Inisialisasi Data

Tambahkan variabel data_nilai sebagai list kosong yang digunakan untuk menyimpan data mahasiswa, setiap elemen dalam list adalah dictionary yang berisi informasi mahasiswa, seperti NIM, Nama, Nilai Tugas, Nilai UTS, Nilai UAS, dan Nilai Akhir yang akan diinputkan :

![gambar](https://github.com/M-Rakha/labpy05/blob/c5e8ec2fe7ac793605e0b328fdd265f7bce7ab66/Cuplikan%20layar%202024-11-25%20191153.png)

## Step 2 : Fungsi lihat_data
Fungsi ini digunakan untuk menampilkan daftar nilai mahasiswa :

- Jika data_nilai kosong, akan muncul pesan "Tidak Ada Data Mahasiswa".
- Jika data_nilai berisi data, ditampilkan dalam bentuk tabel, tabel akan berisikan data yang sudah diinputkan oleh user NIM, Nama, Nilai Tugas, Nilai UTS, Nilai UAS, dan Nilai Akhir.

![gambar](https://github.com/M-Rakha/labpy05/blob/44d4c4449853a97e18ba995a0898e6ca40cc6ae8/Cuplikan%20layar%202024-11-25%20193145.png)

## Step 3 : Fungsi tambah_data

Fungsi ini digunakan untuk menambahkan data nilai mahasiswa ke dalam data_nilai. Langkah-langkahnya, Meminta input dari pengguna untuk NIM, Nama, Nilai Tugas, Nilai UTS, dan Nilai UAS, menghitung nilai akhir dengan bobot (Tugas: 30%, UTS: 35%, UAS: 35%), menambahkan data mahasiswa dalam bentuk dictionary ke list data_nilai. Perintah .append berfungsi untuk menambahkan data/memasukan tambahan data baru ke yang sudah disediakan :

![gambar](https://github.com/M-Rakha/labpy05/blob/36c1e66ba5fef3613451105ab51c4826edfabc8b/Cuplikan%20layar%202024-11-25%20193541.png)

## Step 4 : Fungsi ubah_data
Fungsi ini digunakan untuk mengubah data mahasiswa berdasarkan nomor yang dipilih menampilkan data mahasiswa dengan lihat_data serta meminta pengguna memilih nomor data yang ingin diubah, hal ini mencakup semua data dari NIM, Nama, Nilai Tugas, Nilai UTS, dan Nilai UAS yang diubah, namun ada 2 kondisi dalam kasus ini :

- Jika nomor tidak valid, tampilkan pesan "Data tidak ditemukan".
- Jika valid, memperbarui data dengan input baru.

![gambar](https://github.com/M-Rakha/labpy05/blob/f5c52db95fcfe0de07761890a5dbc60f04eb1132/Cuplikan%20layar%202024-11-25%20194015.png)

## Step 5 : Fungsi hapus_data
Fungsi ini menghapus data mahasiswa dari data_nilai yang sudah tercantumkan datanya pada tabel. outputnya akan menampilkan daftar data dan meminta nomor data yang akan dihapus. Jika nomor valid, data dihapus dengan del :











