Muhammad Daffa Saputra - 2210010440

## Deskripsi

Aplikasi ini adalah program GUI (Graphical User Interface) berbasis Java yang melakukan operasi penjumlahan dua angka. Pengguna dapat memasukkan dua angka, lalu menghitung hasil penjumlahan dengan menekan tombol "Tambah". Program ini juga menyediakan opsi untuk menghapus inputan dan keluar dari aplikasi. Antarmuka pengguna dibangun menggunakan `JFrame` dari Java Swing.

## Fitur
- **Menjumlahkan Dua Angka**: Pengguna dapat memasukkan dua angka dan menekan tombol "Tambah" untuk melihat hasil penjumlahan.
- **Validasi Input**: Program memvalidasi input untuk memastikan bahwa yang dimasukkan adalah angka valid.
- **Menghapus Input**: Tombol "Hapus" memungkinkan pengguna untuk mengosongkan kolom input dan hasil.
- **Keluar dari Aplikasi**: Tombol "Keluar" memungkinkan pengguna untuk menutup aplikasi.

## Cara Menggunakan
1. **Masukkan Angka Pertama**: Ketik angka pertama pada kolom "Angka Pertama".
2. **Masukkan Angka Kedua**: Ketik angka kedua pada kolom "Angka Kedua".
3. **Klik "Tambah"**: Klik tombol "Tambah" untuk mendapatkan hasil penjumlahan dari kedua angka.
4. **Hapus Input**: Klik tombol "Hapus" untuk mengosongkan semua kolom input dan hasil.
5. **Keluar**: Klik tombol "Keluar" untuk menutup aplikasi.

## Instalasi
Untuk menjalankan aplikasi ini, Anda memerlukan:
1. **Java Development Kit (JDK)** versi 8 atau lebih tinggi.
2. **IDE Java** seperti IntelliJ IDEA, Eclipse, atau NetBeans.

Langkah-langkah untuk menjalankan aplikasi:
1. Pastikan Anda memiliki JDK yang terinstal di sistem Anda.
2. Buka proyek ini dalam IDE Java pilihan Anda.
3. Jalankan kelas `AplikasiPertambahanDuaAngka` yang berisi metode `main()`.

## Penjelasan Kode
- **Input Angka**: Terdapat dua kolom input yaitu `txtAngkaPertama` dan `txtAngkaKedua` untuk memasukkan angka pertama dan kedua.
- **Tombol Tambah**: Ketika tombol "Tambah" ditekan, program akan mengambil nilai dari kedua kolom input, kemudian menjumlahkan kedua angka tersebut dan menampilkan hasilnya pada `txtHasil`.
- **Tombol Hapus**: Tombol "Hapus" akan mengosongkan kolom input dan hasil, serta memfokuskan kembali pada kolom input pertama.
- **Tombol Keluar**: Tombol "Keluar" akan menutup aplikasi menggunakan `System.exit(0)`.
- **Validasi Input**: Hanya angka dan tanda titik desimal yang diperbolehkan untuk input. Jika input tidak valid, aplikasi akan menampilkan pesan kesalahan.

## Contoh Penggunaan
1. **Masukkan angka 5** di kolom "Angka Pertama".
2. **Masukkan angka 3** di kolom "Angka Kedua".
3. **Klik tombol "Tambah"** untuk mendapatkan hasil penjumlahan, yang akan menampilkan hasil **8** di kolom "Hasil".

## Tampilan Antarmuka
- **Angka Pertama**: Kolom untuk memasukkan angka pertama.
- **Angka Kedua**: Kolom untuk memasukkan angka kedua.
- **Hasil**: Kolom yang akan menampilkan hasil penjumlahan.
- **Tombol Tambah**: Tombol untuk menambahkan kedua angka.
- **Tombol Hapus**: Tombol untuk menghapus semua input dan hasil.
- **Tombol Keluar**: Tombol untuk keluar dari aplikasi.

## Teknologi yang Digunakan
- **Bahasa Pemrograman**: Java
- **Framework GUI**: Java Swing (`JFrame`, `JButton`, `JTextField`, dll.)

## Troubleshooting
- **Error Input**: Jika Anda memasukkan karakter non-angka atau tanda desimal lebih dari satu, aplikasi akan menampilkan pesan kesalahan: "Masukkan angka yang valid!"
  
