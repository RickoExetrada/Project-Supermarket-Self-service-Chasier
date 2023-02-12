# Project-Supermarket-Self-service-Chasier

A. Latar Belakang Project

Sistem self service chasier adalah sebuah sistem yang dibangun dimana sistem self service ini berarti suatu konsep pelayanan tanpa adanya staf atau pelayan dan pelanggan harus bisa melayani kebutuhannya sendiri. sehingga secara harfiah dapat diartikan bahwa supermarket ini adalah cashier-less dimana para konsumen yang akan menjadi kasir itu sendiri dalam melakukan inputan dari belanja. hal ini tentunya dapat menghemat biaya operational dari supermarket tersebut akan tetapi harus dibangun menggunakan dasar sistem yang baik untuk menghindari kesalahan sistem dalam memperhitungkan hasil belanja.

B. Objectives
Membuat sistem self service cashier dengan menggunakan bahasa Pemograman Python dan konsep OOP
Membuat sistem self service cashier yang memiliki fitur sebagai berikut:
1. Add Item : Menambahkan Barang, Harga, dan Jumlah yang ingin dibeli.
2. Delete Item: Menghapus Barang yang akan dibeli.
3. Reset Item: Mereset seluruh transaksi yang telah dilakukan.
4. Total Item: Melihat hasil keseluruhan belanja yang telah dilakukan.
5. Update ItemQty: update jumlah barang yang ingin diinput
6. Update ItemName: Mengubah nama item yang telah diinput
7. Check Item : melihat seluruh data transaksi yang dimuat
 
C. Flowchart

![FlowChart](https://github.com/RickoExetrada/Gambar/blob/main/Untitled.png)

D. Function and Attribut
1. data_transcaction : Atribut yang berupa dictionary yang berfungsi untuk menyimpan data transaksi yang dilakukan oleh customer
2. add_item : Method yang berfungsi untuk menambahkan list produk yang telah dimasukkan oleh customer yang berisi nama item, kuantitas item, dan harga item
3. update_item_name : Method yang berguna untuk mengubah nama item yang ingin diganti
4. update_item_qty : Method yang berguna untuk mengubah kuantitas item yang di-order
5. delete_item : Method yang digunakan untuk menghapus item tertentu
6. reset_transaction : Method yang digunakan untuk menghapus seluruh data transaksi
7. check_order : Method yang berfungsi untuk menampilkan seluruh data transaksi yang telah dibuat
8. total_price : Method yang digunakan untuk menampilkan total harga seluruh produk

E. TestCase

Test Case 1: Menambahkan Item dengan method Add Item
![Test Case 1](https://github.com/RickoExetrada/Gambar/blob/main/Test%201.PNG)


Test Case 2: Menghapus Item dengan method delete Item
![Test Case 2](https://github.com/RickoExetrada/Gambar/blob/main/Test%202.PNG)

Test Case 3: Mereset Transaction yang telah dibuat
![Test Case 3](https://github.com/RickoExetrada/Gambar/blob/main/Test%203.PNG)

Test Case 4: Melihat total belanja
![Test Case 4](https://github.com/RickoExetrada/Gambar/blob/main/Test%204.PNG)

F. Kesimpulan

Dasar dari program sudah dibuat dan bekerja sesuai dengan yang ditujukan akan tetapi masih ada beberapa hal yang perlu dikembangkan lebih lanjut seperti:
1. User Interface yang kurang ramah karena menggunakan tampilan hitam putih console
2. Dasar Pemograman masih belum terhubung dengan Database

Sekian Dan Terima Kasih
