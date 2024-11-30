# TUGAS PRAKTIKUM 6
# Data Diri

Nama : Safitri Eka Ramadhani

NIM : 312410431

Kelas : TI.24.A.3

# Flowchart 

<img src="Flowchart6.png">

# input dan output dari Praktikum 6

## 1. Input tambah data 

<img src="Input1.png">

<img src="Input(1).png">

## Output tambah data 

<img src="Output1.png">

## 2. Input & Output tampilkan data

<img src="Input & Output2.png">

## 3. Input hapus data

<img src="Input3.png">

## Output hapus data

<img src="Output3.png">

## 4.  Input ubah data

<img src="Input4.png">

## Output ubah data

<img src="Output4.png">

## Output akhir data

<img src="Output Akhir Data.png">

# Penjelasan Algoritma:

## Program ini merupakan aplikasi manajemen data mahasiswa dengan beberapa fungsi utama:

1. Struktur Data:
   - Menggunakan list `data_mahasiswa` untuk menyimpan data mahasiswa
   - Setiap mahasiswa disimpan sebagai dictionary dengan dua kunci: 'nama' dan 'nilai'

2. Fungsi Utama:
   a. `tambah()`:
      - Memungkinkan pengguna menambahkan data mahasiswa baru
      - Meminta input nama dan nilai
      - Menyimpan data ke dalam list `data_mahasiswa`

   b. `tampilkan()`:
      - Menampilkan seluruh data mahasiswa yang tersimpan
      - Jika tidak ada data, menampilkan pesan khusus
      - Menampilkan data dalam format tabel dengan nomor urut

   c. `hapus(nama)`:
      - Menghapus data mahasiswa berdasarkan nama
      - Menggunakan list comprehension untuk membuat list baru tanpa nama yang dimaksud

   d. `ubah(nama)`:
      - Mengubah nilai mahasiswa berdasarkan nama
      - Mencari mahasiswa dengan nama tertentu
      - Memperbarui nilai jika nama ditemukan

   e. `menu()`:
      - Fungsi utama yang menjalankan program
      - Menampilkan menu pilihan
      - Menggunakan loop while untuk terus menampilkan menu
      - Memproses pilihan pengguna dengan percabangan (if-elif)
      - Memberikan opsi untuk keluar dari program

3. Alur Kerja Program:
   - Program dimulai dengan memanggil fungsi `menu()`
   - Pengguna dapat memilih berbagai operasi
   - Program akan terus berjalan hingga pengguna memilih keluar


