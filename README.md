# TUGAS 1 PEMROGRAMAN APLIKASI BERGERAK

AHMAD DANI | 2409116074

# EKSPERIMEN 5: Test Cart Operations

## 1. Tampilan Awal

<img width="200" height="917" alt="image" src="https://github.com/user-attachments/assets/162b8c43-a7fd-40d5-b016-7bb3e9aaa0e7" />

Pada tampilan awal aplikasi, pengguna disajikan daftar produk yang tersedia untuk dibeli. Setiap produk memiliki tombol Add yang berfungsi untuk menambahkan produk tersebut ke dalam keranjang.

## Add product 3x

<img width="200" height="917" alt="image" src="https://github.com/user-attachments/assets/344c31db-9f6c-4bb9-92e7-826947fcc392" />

Ketika tombol Add ditekan pada salah satu produk (misalnya Laptop Gaming), maka:

- Angka indikator pada ikon keranjang di pojok kanan atas akan bertambah.

- Jika produk yang sama ditambahkan sebanyak tiga kali, maka jumlah pada keranjang akan menunjukkan angka 3.



<img width="200" height="917" alt="image" src="https://github.com/user-attachments/assets/0b622e35-b1b0-461b-abdc-68f9db513706" />

Saat ikon keranjang ditekan, pengguna akan diarahkan ke halaman keranjang yang menampilkan daftar produk yang telah ditambahkan. Pada contoh ini, terdapat Laptop Gaming dengan jumlah 3 item

## 2. Add different products

<img width="200" height="917" alt="image" src="https://github.com/user-attachments/assets/50359cec-a1fd-403c-83dc-3cb98806d264" />

Jika pengguna menambahkan beberapa jenis produk yang berbeda (misalnya Laptop Gaming, Smartphone, dan Wireless Headphone), maka:

- Ikon keranjang akan menampilkan angka sesuai jumlah jenis produk yang ditambahkan.

- Halaman keranjang akan menampilkan seluruh produk yang telah dipilih beserta jumlah masing-masing.
<img width="200" height="917" alt="image" src="https://github.com/user-attachments/assets/788b26bb-3e71-4f55-a82a-ad03b3d1084e" />

Hal ini menunjukkan bahwa sistem dapat menangani lebih dari satu jenis produk dalam satu transaksi.

## 3. Increase quantity

<img width="200" height="917" alt="image" src="https://github.com/user-attachments/assets/e2ef9189-0f85-473f-877d-69a38bdfce1f" />
Pengguna dapat menambah jumlah produk langsung dari halaman keranjang dengan menekan tombol "+" pada produk yang diinginkan.

Contohnya:

- Wireless Headphone yang awalnya berjumlah 1 dapat ditambah menjadi 2.

- Total harga akan otomatis diperbarui sesuai dengan jumlah terbaru produk di dalam keranjang.

Fitur ini memastikan perhitungan harga dilakukan secara dinamis.

## 4. Decrease to 1

<img width="200" height="917" alt="image" src="https://github.com/user-attachments/assets/29f28f4f-464e-4b74-92e7-dcdb325975f0" />

Untuk mengurangi jumlah produk, pengguna dapat menekan tombol "-" pada produk terkait.

Contohnya:

- Laptop Gaming yang sebelumnya berjumlah lebih dari satu dapat dikurangi hingga tersisa 1.

- Total harga akan menyesuaikan secara otomatis setelah pengurangan jumlah.

## 5. Decrease to 0

<img width="200" height="917" alt="image" src="https://github.com/user-attachments/assets/a8a78424-7fa4-4989-8186-eb2984cfbdb4" />

Jika tombol "-" terus ditekan hingga jumlah produk mencapai 0, maka produk tersebut akan otomatis dihapus dari daftar keranjang.

Fitur ini memudahkan pengguna dalam mengelola isi keranjang tanpa perlu tombol hapus terpisah untuk setiap item.

## 6. Clear all

<img width="200" height="917" alt="image" src="https://github.com/user-attachments/assets/0c321428-bc20-4e68-a576-2ff1d07d5b1a" />

Aplikasi juga menyediakan fitur untuk menghapus seluruh isi keranjang sekaligus melalui ikon tong sampah di pojok kanan atas halaman keranjang.

Langkah-langkahnya:

- Tekan ikon tong sampah.

- Akan muncul dialog konfirmasi untuk memastikan tindakan.

- ilih Cancel untuk membatalkan.

- Pilih Clear untuk mengosongkan seluruh isi keranjang.

<img width="200" height="917" alt="image" src="https://github.com/user-attachments/assets/d8bc774c-0972-433b-a84e-b5784d5d06ff" />

Setelah memilih Clear:

- Semua produk di dalam keranjang akan terhapus.

- Ikon tong sampah akan hilang karena keranjang sudah kosong.

- Indikator jumlah pada ikon keranjang juga akan kembali kosong.

## 7. Navigate back

<img width="200" height="917" alt="image" src="https://github.com/user-attachments/assets/3ef73928-4c19-4529-bb79-633250b1627e" />

Tombol Continue Shopping memungkinkan pengguna kembali ke halaman utama untuk memilih produk lainnya.

Jika sebelumnya keranjang telah dikosongkan, maka:

- Indikator jumlah pada ikon keranjang tidak akan menampilkan angka.

- Pengguna dapat memulai kembali proses pemilihan produk dari awal.
