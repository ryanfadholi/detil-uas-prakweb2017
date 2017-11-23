## Outline
1. Deskripsi Soal
2. Rubrik Penilaian
3. File Database
4. Contoh Implementasi Website
5. Form Pengumpulan

### Deskripsi Soal

> Buatlah sebuah portal data mahasiswa, dimana pengguna dapat melihat dan memasukkan data mahasiswa baru. 

Website akan dinilai sesuai implementasi fitur-fitur yang terdapat di rubrik dibawah. Setiap fitur memiliki jumlah poin sendiri-sendiri. Poin-poin yang tidak dibahas pada rubrik dibawah *(misalnya layout, template)* artinya bersifat bebas, tergantung kreativitas masing-masing individu. **Khusus untuk struktur database dan contoh data sudah ditentukan, silahkan download file .sql yang disediakan dan import ke MySQL masing-masing.**

Form pengumpulan dan contoh implementasi sebagai referensi ada di bagian bawah. Sekali lagi, contoh implementasi HANYA bersifat referensi, dan tidak perlu diikuti sama persis. Cukup penuhi poin-poin yang ada di rubrik, sisanya terserah anda.

### Rubrik Penilaian

Rubrik penilaian dibagi menjadi beberapa sub-bagian:

#### Penilaian Utama

##### Framework
- **(10 Poin)** Menggunakan framework CodeIgniter.
- **(10 Poin)** Menggunakan framework Bootstrap.
##### Navigation Bar
- **( 5 Poin)** Website memiliki sebuah Navigation Bar (selanjutnya disebut **Navbar**).
- **( 5 Poin)** Navbar menyediakan link menuju halaman tampilan data dan halaman input data.
- **( 5 Poin)** Navbar dinamis (Jika user berada di satu halaman, maka link ke halaman tersebut diberi tanda). 
  *Misalnya pada contoh, link ke halaman yang sedang dibuka user di-bold.*
#### Halaman Tampilan Data
- **(10 Poin)** Website dapat menampilkan seluruh data mahasiswa yang ada dalam bentuk tabel.
- **( 5 Poin)** Data yang ditampilkan diurutkan berdasarkan nama mahasiswa.
- **(10 Poin)** Website menggunakan konsep Pagination saat menampilkan data (Jumlah data per halaman tidak ditentukan).
- **( 5 Poin)** Navigasi Pagination pada Website dinamis (Bentuk navigasi Pagination tidak ditentukan)
  *Misalnya pada contoh, halaman data yang sedang dibuka oleh user di-highlight. Lalu jika user berada di halaman pertama maka tombol "Previous" akan dimatikan, sedangkan jika user berada di halaman terakhir maka tombol "Next" dimatikan.*
#### Halaman Input Data Baru
- **(10 Poin)** Website memiliki satu halaman form yang berisi field **NIM**, **nama**, **Tanggal Lahir**, dan **Jurusan**.
- **(10 Poin)** Form dapat memasukkan nilai ke dalam database.
- **(10 Poin)** Form memiliki field "Fakultas" yang dapat dipilih user, dimana field tersebut mengubah pilihan pada field Jurusan secara dinamis.
- **( 5 Poin)** Setelah user menekan "Submit", maka Website kembali ke halaman utama dan memberi feedback ke user bahwa data berhasil dimasukkan.
*Misalnya pada contoh, akan keluar kotak berwarna hijau pada bagian atas halaman setelah user memasukkan data*

> Total Penliaian Utama: **100 Poin**

### Bonus
- **( 5 Poin)** Ada logo Unsri pada Navbar.
- **( 5 Poin)** Di halaman form, User tidak dapat melakukan "Submit" sebelum seluruh field pada form terisi.

> Total Penilaian Utama + Bonus: **110 Poin**

## File Database

File .SQL berisi struktur databse dan beberapa contoh datanya. [Download disini](https://drive.google.com/file/d/1h1KOmqr_cHJ1855LEx3rQPu3yE_Aat9y/view?usp=sharing)

## Contoh Implementasi Website

Contoh Website dapat dilihat disini.

## Form Pengumpulan

Website **HARUS** diupload ke webhosting. Jika ada bagian-bagian yang tidak anda kerjakan secara sempurna (hanya setengah jadi, ada bug, dsb), mohon tuliskan dan jelaskan pada kolom yang disediakan pada form.

