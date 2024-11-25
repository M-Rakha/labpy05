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

![gambar](https://github.com/M-Rakha/labpy05/blob/b17643c0c968c2b67bb33b7a21cc711aaa21c71d/Cuplikan%20layar%202024-11-25%20194234.png)

## Step 6 : Fungsi cari_data

Fungsi ini mencari data mahasiswa berdasarkan nama yang sudah tertera/data pada tabel data dengan menggunakan list comprehension untuk mencari nama yang cocok (case-insensitive), jika ditemukan akan menampilkan data mahasiswa jika tidak, menampilkan pesan "Data tidak ditemukan" :

![gambar](https://github.com/M-Rakha/labpy05/blob/f84fd4f15cef2f3f69dd619a864d1dbd1db86b38/Cuplikan%20layar%202024-11-25%20194529.png)

## Step 7 : Main Loop

Loop ini merupakan antarmuka utama program selanjutnya akan menampilkan menu pilihan berdasarkan input pengguna, pilihannya yaitu:

- L: Memanggil lihat_data.
- T: Memanggil tambah_data.
- U: Memanggil ubah_data.
- H: Memanggil hapus_data.
- C: Memanggil cari_data.
- K: Keluar dari program.

Jika input tidak valid, menampilkan pesan "Menu tidak valid".

![gambar](https://github.com/M-Rakha/labpy05/blob/d542acf48427c0c11baadde9e78ae7ce998d6ade/Cuplikan%20layar%202024-11-25%20194809.png)

## Step 8 : Run Program

Tahap akhir adalah uji coba code program yang sudah dibuat dengan mencoba berbagai kemungkinan yang ada.

### Case 1 :

Kondisi pertama kita akan coba melihat tabel dengan inputkan L tampa menambahkan data/masih kosong, maka akan ditampilkan isi tabel masih belum ada datanya :

![gambar](https://github.com/M-Rakha/labpy05/blob/2534be3f1b5b61636f7a931fdc5561625494eaf5/Cuplikan%20layar%202024-11-25%20195253.png)

### Case 2 :

Kondisi kedua selanjutnya mencoba menambahkan data nilai mahasiswa pada tabel, dengan menginputkan T untuk menambahkan data nilai.

Tambahkan data nilai :
- NIM : 312410387
- Nama : Dafa Maulana
- Nilai Tugas : 90
- Nilai UTS : 85
- Nilai UAS : 79





