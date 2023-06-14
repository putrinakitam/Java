# App.java

kelas yang berisi method main untuk menjalankan aplikasi

## Metode

`main(String[] args)`: Metode utama yang menjalankan `App.main(args)` untuk memulai aplikasi.

# config

terdapat satu class pada file ini yaitu `DbController.java`

## MyConfig.java

`MyConfig.java` adalah kelas yang berfungsi untuk membuat koneksi menuju database menggunakan JDBC

## getConnection.java

Membuat koneksi dengan database menggunakan URL, username, dan password yang telah ditentukan.

## DbController.java

`DbController.java` adalah kelas yang bertanggung jawab untuk mengelola koneksi, pernyataan, dan hasil set data dalam operasi database. 

# Layouts

terdapat 5 class pada file ini yaitu `Delete.java`, `Edit.java`, `Insert.java`, `Menu.java`, `Read.java`

## Read.java

`Read.java` adalah kelas yang bertanggung jawab untuk membaca dan mencetak data dari tabel `tb_produk` ke konsol.

### Metode

- `showReadData()`: Mengeksekusi pernyataan SQL untuk mengambil data dari tabel `tb_produk` dan mencetaknya ke konsol.

## Edit.java

`Edit.java` adalah kelas yang bertanggung jawab untuk mengubah data dalam tabel `tb_produk`.

### Metode

- `showEditData()`: Meminta input pengguna untuk ID data yang akan diubah, serta nilai baru untuk NAMA, POWER, dan DEFENSE. Mengeksekusi pernyataan SQL untuk mengubah data dalam tabel `tb_produk`.

## Insert.java

`Insert.java` adalah kelas yang bertanggung jawab untuk memasukkan data baru ke dalam tabel `tb_produk`.

### Metode

- `showInsertData()`: Meminta pengguna untuk memasukkan data baru, kemudian mengeksekusi pernyataan SQL untuk memasukkan data tersebut ke dalam tabel `tb_produk`.

## Delete.java

`Delete.java` adalah kelas yang bertanggung jawab untuk menghapus data dari tabel `tb_produk`.

### Metode

- `showDeleteData()`: Meminta input pengguna untuk ID data yang akan dihapus, kemudian mengeksekusi pernyataan SQL untuk menghapus data dari tabel `tb_produk`.

## Menu.java

`Menu.java` adalah kelas utama yang berfungsi sebagai antarmuka pengguna untuk mengakses fitur-fitur CRUD pada tabel `tb_produk`.

### Metode

- `showMenu()` : menampilkan semua pilihan yang bisa dipilih oleh pengguna.

- `selectMenu.java` : method yang bertujuan agar pengguna dapat memilih dan mengakses fitur-fitur yang ada di Menu.

# Models

terdapat 1 class dalam file ini yaitu `Produk.java`

## Hero.java

`Produk.java` adalah kelas yang merepresentasikan objek hero dalam aplikasi.

### Atribut

- `id`: ID barang.
- `nama`: Nama barang.
- `harga`: Harga barang.
- `jumlah`: Jumlah stok barang.

### Metode

- Metode setter dan getter untuk setiap atribut.
