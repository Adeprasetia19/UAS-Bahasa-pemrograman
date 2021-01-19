# UAS-Bahasa-pemrograman
Soal
Berikut ini adalah soal Ujian Akhir Semester(UAS) 1 yang diberikan oleh dosen saya
soal.png
Disitu tertulis kita disuruh membuat package dan modul lalu jelaskan di github berserta gambar screen shotnya

Penyelesaian
Oke Berikut adalah syntax - syntax yang saya gunakan untuk mengerjakan soal diatas
jawaban.png

Package model(daftar_nilai) Click Here
Package view(input_nilai) Click Here dan view(view_nilai) Click Here
modul main Click Here
Setelah kalian melihat syntax diatas saya akan menjelaskannya satu - persatu:

Daftar_Nilai
Dictionary
dictionary.png
Penjelasan:

Disini kita menggunakan dictionary ya untuk menyimpan inputan data mahasiswa
Def tambahkan
tambahkan.png
Penjelasan:

Dibagian ini kita gunakan print untuk penulisan bagian input data mahasiswa nanti agar terlihat rapih
Def hapus
hapus.png
Penjelasan:

Disini kita buat inputan yang menginput nama
Gunanya untuk menghapus data mahasiswa dari nama mahasiswa itu sendiri
Kita gunakan del untuk fungsi menghapus datanya
(If)Jika mahasiswa tersebut ada maka data mahasiswa tersebut akan terhapus
(Else)Jika nama mahasiswa tersebut tidak ada maka datanya tidak akan ditemukan
Def ubah
ubah.png
Penjelasan:

Disini kita hampir sama dengan yang hapus, kita gunakan inputan nama untuk mengubah NIM, Nilai Tugas, Ujian Tengah Semester(UTS), ataupun Ujian Akhir Semester(UAS)
Lalu setelah kita memasukkan nama maka dictionary akan mengeksekusi program menggunakan keys untuk mencari data dari nama mahasiswa tersebut
(If)Jika nama mahasiswa tersebut ketemu atau ada didalam data maka program akan masuk ke inputan NIM, Nilai Tugas, Nilai UTS, dan Nilai UAS yang baru
(Else)Jika nama mahasiswa tersebut tidak ada didalam data maka program akan memunculkan tulisan atau perintah bahwa data mahasiswa tidak ada
Def cari
cari.png
Penjelasan:

Fungsinya sama dengan Def tambahkan
Input_Nilai
From dan import
from.png
Penjelasan:

From digunakan untuk memanggil package sementara import untuk tujuan yang kita pilih yaitu modul daftar_nilai
Lalu kita gunakan import data_mahasiswa itu gunanya agar saat kita menginputkan data atau setiap kali kita menambah data maka data mahasiswa secara otomatis akan masuk kedalam dictionary meskipun beda atau terpisah package dan juga modulnya
Def tambah data
tambah_data.png
Penjelasan:

Disini kita buat inputan karena tadi kita sudah membuat kata - kata outputnya kali ini kita cukup membuat inputan data mahasiswanya saja
Jangan lupa gunakan perkalian untuk menghitunghasil total atau rata- ratanya
View_Nilai
From dan import
from.png
Penjelasan:

Fungsinya sama saja dengan yang ada dibagian Input_Nilai
Def tampil
tampil.png
Penjelasan:

Disini kita buat sebuah tabel untuk menampilkan data - data dan nama - nama mahasiswa didalam dictionary
(If)Jika terdapat data maka data dan nama mahasiswa tersebut akan muncul
Disini kita menggunakan for untuk melakukan perulangan nomor urut
(Else)Jika kita belum menginputkan data sama sekali maka akan muncul tulisan "tidak ada data"
Def cari data
cari_data.png
Penjelasan:

Tadi kita sudah buat print sama seperti dibagian Input_Nilai
Kita akan langsung membuat inputan dengan format nama untuk mencari data dari mahasiswa yang sedang kita cari
(If)Jika data mahasiswa yang dicari ada didalam dictionary maka data baik Nama, NIM, Nilai Tugas, Nilai UTS, dan Nilai UAS akan muncul
(Else)Jika data mahasiswa yang dicari tidak ada didalam dictionary maka akan muncul tulisan "datanya tidak ada"
Main
From dan import
memanggil_modul.png
Penjelasan:

Sama seperti sebelumnya hanya saja disini sedikit berbeda
From disini kita tulis package.modulnya lalu import fungsi(def) tadi
Karena dibagian main ini kita akan menggunakan atau membuat syntax pilihan menu
While True
pilih_menu.png
Penjelasan:

Kita gunakan print untuk membuat pilihan menunya
Lalu kita buat inputan untuk memilih menu nanti ketika program dijalankan
(If dan Elif)Kita gunakan karena kita akan membuat cabang pilihan yang banyak
Lalu dibawahnya kita tambahkan juga fungsi - fungsi yang sudah kita buat tadi
Pada perintah ke 6 kita gunakan break untuk keluar dari program yang kita jalankan
(Else)Jika kita tidak memilih salah satu menu tersebut maka akan muncul peringatan "pilih menu yang tersedia diatas"
Setelah semmuanya selesai maka kita akan menjalankan/run syntax untuk mengerun atau menjalankan syntax harus yang main karena pilihan menunya ada di main Berikut adalah tampilan dari program atau syntax- syntax yang sudah kita buat tadi

Tambah data mahasiswa
tambah_akbar.png
tambah_qiqi.png

Tampilkan data mahasiswa
Jika kita sudah memasukkan atau menginputkan data mahasiswa
tampilkan_data.png
Jika kita belum menginputkan data mahasiswa
tidak_ada_data.png

Menghapus data mahasiswa
Jika kita sudah memasukkan atau menginputkan data mahasiswa
hapus_data_qiqi.png
Jika kita belum menginputkan data mahasiswa
pencarian_tidak_ada.png
Tampilan data jika kita sudah berhasil menghapus data mahasiswa
tampilkan_data_setelah_dihapus.png

Mengubah data mahasiswa
Jika kita sudah memasukkan atau menginputkan data mahasiswa
ubah_data.png
Jika kita belum menginputkan data mahasiswa
tidak_ada_data_dirubah.png
Tampilan data jika kita sudah berhasil mengubah data mahasiswa
tampilkan_data_setelah_diubah.png

Mencari data mahasiswa
Jika kita sudah memasukkan atau menginputkan data mahasiswa
mencari_data_qiqi.png
Jika kita belum menginputkan data mahasiswa
data_tidak_bisa_dicari.png

Kelar dari program
keluar_dari_program.png

Pilih menu yang tersedia diatas
pili_menu_tersedia.png

Oke sekian penjelasan dan selesai sudah tugas Ujian Akhir Semester(UAS) 1 untuk Mata Kuliah Bahasa Pemrograman
Sekian Terimakasih Banyak
