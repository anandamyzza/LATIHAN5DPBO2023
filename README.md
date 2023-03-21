## Janji
Saya Ananda Myzza Marhelio NIM 2100702 mengerjakan soal Latihan 5 dalam mata kuliah Desain Pemrograman Berorientasi Objek untuk keberkahanNya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. Aamiin.

# Deskripsi Tugas Latihan 5 DPBO 2023
Link download [starter project](https://drive.google.com/file/d/1TEnEay74nhGcSS9PPzQcxksIlaQhTiZ2/view?usp=sharing)

* Tambahkan lebih banyak properti (component type: apa saja, selain text field)
* Tambahkan metode untuk reset form
* Refresh tabel setelah update dan delete
* Tambahkan permintaan konfirmasi sebelum delete
* Build project (generate .jar file)

**Hasil yang diharapkan:**

![image](https://user-images.githubusercontent.com/100767177/226620357-f07ff521-b842-429b-b1e3-0098e4363c43.png)

## Desain Program
Terdapat 2 class di program ini, yaitu:
1. **Class Mahasiswa** memiliki 4 atribut yaitu nim (Nomor Induk Mahasiswa), nama, nilai, dan gender (Jenis Kelamin). Setiap atribut pada class ini diberi setter dan getter.
2. **Class Menu** yang berisi metode-metode untuk menampilkan, menambahkan, mengubah, dan menghapus data mahasiswa pada tabel.

### Desain GUI dan Hasil Program
![Dokumentasi](https://user-images.githubusercontent.com/100767177/226622386-01b0ca61-b602-4234-9fcf-0c94fbaa44dc.png)

## Alur Program
Program akan menampilkan tampilan form yang berisi tiga textfield untuk menginput data NIM, Nama, dan Nilai serta satu ComboBox/Dropdown untuk menginput data gender (Jenis kelamin). Pengguna dapat menambahkan data dengan mengisi form tersebut lalu menekan tombol `Add`, mengubah data mahasiswa dengan menekan data mahasiswa dalam tabel lalu mengubah data melalui form yang ada lalu menekan tombol `Update`, dan menghapus data mahasiswa dengan menekan data mahasiswa dalam tabel lalu menekan tombol `Delete`. Form akan ter-reset setelah menekan tombol `Cancel` atau melakukan metode-metode tersebut.

## Dokumentasi
### Tampilan Awal, Add dan Update Data
![AddUpdate](https://user-images.githubusercontent.com/100767177/226629086-c62bca47-ff2f-4151-a3b4-ea14f2eb6fb1.png)

### Delete Data
![Delete](https://user-images.githubusercontent.com/100767177/226629161-69a6ac3b-c281-4cda-9eed-a8c40f04a003.png)
