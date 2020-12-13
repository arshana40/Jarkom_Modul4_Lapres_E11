# Jarkom_Modul4_Lapres_E11

## Pengerjaan dengan VLSM
### Pengalokasian IP
![soal](https://github.com/arshana40/Jarkom_Modul4_Lapres_E11/blob/main/Screenshoot/soal.png)\
Langkah awal yang dilakukan adalah menentukan jumlah alamat IP yang dibutuhkan dengan menjumlahkan semua kebutuhan berdasarkan soal:\
![gambar0](https://github.com/arshana40/Jarkom_Modul4_Lapres_E11/blob/main/Screenshoot/pt1.png)\
![gambar1](https://github.com/arshana40/Jarkom_Modul4_Lapres_E11/blob/main/Screenshoot/colum1.png)\
Dari hasil penjumlahan, diketahui netmask yang akan digunakan adalah netmask /19.\
Langkah berikutnya adalah membuat tree sebagai acuan pengalokasian:\
![gambar3](https://github.com/arshana40/Jarkom_Modul4_Lapres_E11/blob/main/Screenshoot/Tree.png)\
Dengan menggunakan tree sebagai acuan, didapatkan alokasi IP sebagai berikut:\
![gambar4](https://github.com/arshana40/Jarkom_Modul4_Lapres_E11/blob/main/Screenshoot/col2.png)\
### Routing
![gambar5](https://github.com/arshana40/Jarkom_Modul4_Lapres_E11/blob/main/Screenshoot/rout1.png)\
### Implementasi pada CPT
![isi](https://github.com/arshana40/Jarkom_Modul4_Lapres_E11/blob/main/Screenshoot/wow1.png)\
Isikan pada tiap item yang tersedia seperti pada perencanaan sebelumnya, lalu dapat dilakukan ujicoba untuk mengirim data
![coba](https://github.com/arshana40/Jarkom_Modul4_Lapres_E11/blob/main/Screenshoot/wow2.png)\

## Pengerjaan dengan CIDR
### Pengalokasian IP
Langkah awal yang dilakukan adalah dengan menggabungkan subnet-subnet yang berdekatan dimulai dari yang paling jauh dari root (SURABAYA dalam kasus ini)\
![gambar6](https://github.com/arshana40/Jarkom_Modul4_Lapres_E11/blob/main/Screenshoot/pt1.png)\
![gambar7](https://github.com/arshana40/Jarkom_Modul4_Lapres_E11/blob/main/Screenshoot/pt2.png)\
![gambar8](https://github.com/arshana40/Jarkom_Modul4_Lapres_E11/blob/main/Screenshoot/pt3.png)\
![gambar9](https://github.com/arshana40/Jarkom_Modul4_Lapres_E11/blob/main/Screenshoot/pt4.png)\
![gambar10](https://github.com/arshana40/Jarkom_Modul4_Lapres_E11/blob/main/Screenshoot/pt5.png)\
![gambar11](https://github.com/arshana40/Jarkom_Modul4_Lapres_E11/blob/main/Screenshoot/pt6.png)\
![gambar12](https://github.com/arshana40/Jarkom_Modul4_Lapres_E11/blob/main/Screenshoot/pt7.png)\
Kemudian, dari langkah penggabungan tersebut dapat dibuat tree:
![gambar13](https://github.com/arshana40/Jarkom_Modul4_Lapres_E11/blob/main/Screenshoot/trre2.png)\
Dari tree, berikut adalah hasil pembagian IP:
![gambar14](https://github.com/arshana40/Jarkom_Modul4_Lapres_E11/blob/main/Screenshoot/fnl.png)\
### Implementasi pada UML
Praktikan belum sanggup menyelesaikan implementasi tepat waktu

# Permasalahan Selama Pengerjaan
- Kurangnya komunikasi menyebabkan terlambatnya praktikan dalam mengontak Asisten Dosen penguji
- Ukuran topologi yang lebih besar dari sebelumnya membuat praktikan kesulitan dalam memperbaiki dan mencari permasalahan karena ada lebih banyak hal yang harus diperiksa dibandingkan praktikum-praktikum sebelumnya
- Gangguan koneksi mengakibatkan UML tertutup secara tiba-tiba, membuat pengerjaan terhambat karena proses menyiapkan uml lebih lama dibandingkan sebelumnya
- Kesalahan dalam menggabungkan subnet pada pengerjaan secara CIDR membuat penghitungan harus dilakukan ulang

