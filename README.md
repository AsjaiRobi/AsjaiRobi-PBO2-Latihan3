# AsjaiRobi-PBO2-Latihan3

# Aplikasi Pengelolaan Kontak

Aplikasi ini adalah desktop-based app berbasis Java yang digunakan untuk mengelola daftar kontak. Aplikasi ini memiliki fitur untuk menambahkan, mengedit, menghapus, mencari, mengekspor, dan mengimpor kontak.
Fitur Utama

    Tambah Kontak
    Menambahkan kontak baru dengan informasi seperti nama, nomor telepon, dan kategori.

    Edit Kontak
    Memperbarui data kontak yang telah disimpan.

    Hapus Kontak
    Menghapus kontak yang dipilih dari daftar.

    Pencarian Kontak
    Mencari kontak berdasarkan nama atau nomor telepon.

    Ekspor ke CSV
    Menyimpan semua data kontak ke dalam file CSV.

    Impor dari CSV
    Memuat data kontak dari file CSV ke dalam aplikasi.

Cara Menggunakan

    Menjalankan Aplikasi
    Jalankan file .jar aplikasi menggunakan perintah berikut:

    java -jar PengelolaanKontak.jar

    Pengelolaan Kontak
        Tambahkan kontak melalui kolom input di bagian kiri, kemudian klik tombol Tambah.
        Edit kontak dengan memilih kontak pada tabel, mengubah data di kolom input, lalu klik tombol Edit.
        Hapus kontak dengan memilih kontak pada tabel, lalu klik tombol Hapus.
        Cari kontak dengan mengetik nama atau nomor telepon di kolom pencarian, lalu klik tombol Cari.

    Ekspor/Impor CSV
        Ekspor data dengan mengklik tombol Ekspor file ke csv, file akan disimpan dengan nama kontak.csv di direktori kerja.
        Impor data dengan menempatkan file kontak.csv di direktori kerja, lalu klik tombol Impor.

File CSV

    Format Header CSV:

ID,Nama,Nomor,Kategori

Contoh Isi CSV:

1,John Doe,08123456789,Teman
2,Jane Smith,08198765432,Rekan Kantor
