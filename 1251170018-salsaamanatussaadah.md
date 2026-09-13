# Tugas-algoritma-Pertemuan 1  
**Mata Kuliah:** Algoritma & Struktur Data  
**Nama:** Salsa Amanatussaadah  
**NIM:** 1251170018  
 
## A. Studi Kasus: Algoritma Pendaftaran & Otentikasi Pengguna Baru di Aplikasi MObile.  
### Input:  
1.Email  
2.Password  
3.Kode OTP  
### Langkah-langkah:  
1.Pengguna meginput email dan password  
2.sistem akan memvalidasi format email(mengandung "@" dan domain valid)  
3.Sistem memvalidasi password(misal minimal 8 karakter, biasanya terdiri dari huruf dan angka)  
4.Jika format valid maka sistem akan menyimpan data sementara( akun belum aktif) 
5.Sistem akan membuat(Generate) kode OTP 6 digit secara acak  
6.Sistem mengirim kode OTP ke email pengguna  
7.pengguna menginput kode OTP yang dikirim  
8.Sistem akan mencocokkan kode OTP input dengan kode OTP yang dikirim  
9.Jika kode OTP cocok dan belum kadaluwarsa(misal kurang dari 5 menit) maka akun akan aktif otomatis  
10.Jika kode OTP salah atau sudah kadaluwarsa tampilkan error dan input ulang( akan diberi waktu maksimal 3 kali percobaan)  
11.Selesai akun terbuat  
### Output:  
1.Akun berhasil terbuat dan aktif  
2.Pesan error  
### Definiteness(kepastian):  
setiap langkah diurutkan secara jelas dan tidak ada unsur ambiguitas seperti aturan validasi email dan password sudah pasti harus dengan format mengandung "@"atau minimal 8 karakter begitu pula dengan pencocokkan OTP harus sama persis dan belum kadaluwarsa. 
### finiteness(keterbatasan):  
Proses pasti berakhir dengan jelas di sejumlah langkah tertentu, tidaak terus-menerus berjalan tanpa batas. seperti:  
1.Batas waktu OTP 5 menit  
2.Batas percobaan maksimal 3 kali  
### Effectiveness (efektivitas)  
setiap langkah dapat benar benar dilakukan secara nyata oleh sistem  

## B. Analisis pemilihan struktur data:  
### 1. skenario 1 (Fitur Undo/Redo)  
Struktur Data Terpilih: Queue  
Alasan: karna
### 2. skenario 2 (Peta Navigasi Rute Perjalanan)  
Struktur Data Terpiih: Graph  
Alasan: karna struktur data graph ini akan menghubungkan dari 1 titik ke titik titik lainnya sama hal dengan peta perjalanan    
### 3. Skenario 3 ( Sitem Login Pengguna Berbasis Username)  
Struktur Data Terpilih:  
Alasan:  

## C. Eksplorasi Analogi Mandiri  
### Pilihan Struktur Data: 
i. Nama Analogi kehidupan sehari-hari:  
ii. Cara kerja analogi tersebut:  
iii. Mengapa analogi tersebut mencerminkan kelebihan atau kekurangnan dari strukur data yang dipilih:

