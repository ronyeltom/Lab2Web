# Lab2Web
### RONY ELTOM ATIBMAN
### TI.20.D.1



## 1. Buatlah dokumen HTML seperti berikut
![Gambar 1](screenshot/s1.png)
selanjutnya buka pada web browser melihat hasilnnya
![Gambar 2](screenshot/s2.png)

## 2. Mendekklarasi CSS Internal
kemudian tambahkan deklarasi CSS INternal seperti berikut pada bagian head dokumen
![Gambar 3](screenshot/s3.png)
Selanjutnya simpan perubahan yang ada, dan lakukan refresh pada browser untuk melihat hasilnya
![Gambar 4](screenshot/s4.png)

## 3. Menambahkan Inline CSS
Kemudian tambahan deklarasi Inline CSS pada tag `<p>` seperti berikut.
![Gambar 5](screenshot/s5.png)
simpan kembali dan refresh kembali browser untuk melihat perubahannya.
![Gambar 6](screenshot/s6.png)

## 4. Membuat CSS Ekternal
Buatlah File dengan nama <b>style_eksternal.css</b> kemudian buatlah deklarasi CSS seperti berikut
![Gambar 7](screenshot/s7.png)
Kemudian tambahkan tag `<link>` untuk merujuk file css yang dibuat pada bagian `<head>`
![gambar 8](screenshot/s8.png)
Selanjutnya refresh kembali browser untuk melihat perubahannya.
![Gambar 9](screenshot/s9.png)

## 5. Menambahkan CSS Selector
Selanjutnya menambahkan CSS selector menggunakan ID dan Class Selector. pada file <b>STyle_eksternal.css</b> tambahkan kode berikut.
![gambar 10](screenshot/s10.png)
kemudian  simpan kembali dan refresh browser untuk melihat perubahannya.
![Gambar 11](screenshot/ss2.png)


# pertanyaan dan tugas
### 1. lakukan EKsperimen dengan mengubah dengan nilai dan menambah properti dan nilai pada kode CSS dnegan mengacu pada CSS Cheat sheet yang di berikan pada file terpisah yang diberikan pada file terpisah dari modul ini 
* saya melakukan beberapa experimen seperti mengubah nilai yang hasilnya mengubah ukuran ataupun warna dan mengganti bacground
![Gambar 12](screenshot/nomor.png)

### 2. apa perbedaan pendeklarasian CSS elemen h1{...} dengan #intro h1{...}? berikan penjelasan
* Pendeklarasian CSS elemen h1 mengubah tampilan seleuruh elemen yang memiliki tag h1, sedangkan #intro h1 hanya mengubah tampilan elemen h1 yang memiliki #intro h1.

### 3. apabila ada deklarasi CSS secara INternal, lalu ditmabahkan CSS eksternal dan inline CSS pada elemen sama. deklarasi manakah yang akan di tampilkan pada browser? berikan penjelasan dan contohnya!
* setelah saya mencoba, jika mendeklarasi CSS pada elemen yang sama namun dengan isi deklarasi berbeda, maka semua dekalarasi CSS tersebut akan ditampilkan. contohnya :
![Gambar 13](screenshot/nomor1a.png)
![Gambar 14](screenshot/nomor1b.png)

* Namun jika isi dari ketiga deklarasi CSSnya sama semua, maka browser hanya menampilkan salah satunnya, dengan urutan inline CSS, Eksternal CSS, dan yang terakhir Internal CSS.
![Gambar](screenshot/nomor1c.png)

### 4. pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan di tampilkan pada browser? berikan penjelasan dan contohnya!
* kedua deklarasi tersebut akan tampil, namun selector ID yang akan tammpiljika deklarasinya ada yang sama antara ID dan Class.
![Gmbar](screenshot/nomor4.png)
