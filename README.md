# Outline
1. Deskripsi Soal
2. Waktu Pengerjaan
3. Rubrik Penilaian
4. File Database
5. Contoh Implementasi Website
6. Form Pengumpulan

# Deskripsi Soal

> Buatlah sebuah portal data mahasiswa, dimana pengguna dapat melihat dan memasukkan data mahasiswa baru. 

Website akan dinilai sesuai implementasi fitur-fitur yang terdapat di rubrik dibawah. Setiap fitur memiliki jumlah poin sendiri-sendiri. Poin-poin yang tidak dibahas pada rubrik dibawah *(misalnya layout, template)* artinya bersifat bebas, tergantung kreativitas masing-masing individu. **Khusus untuk struktur database dan contoh data sudah ditentukan, silahkan download file .sql yang disediakan dan import ke MySQL masing-masing.**

Form pengumpulan dan contoh implementasi sebagai referensi ada di bagian bawah. Sekali lagi, contoh implementasi HANYA bersifat referensi, dan tidak perlu diikuti sama persis. Cukup penuhi poin-poin yang ada di rubrik, sisanya terserah anda.

# Waktu Pengerjaan

Soal dikerjakan dalam waktu +-2 minggu, dengan deadline pengumpulan pada form yang telah disediakan **Jumat, 8 Desember 2017 Jam 13:00 WIB**. Waktu mengacu pada timestamp yang muncul pada hasil submit form.

# Rubrik Penilaian

Ada 2 bagian, yaitu Penilaian Utama dan Penilaian Bonus. Rubrik Penilaian Utama dibagi lagi menjadi beberapa sub-bagian:

### Penilaian Utama
> Total Penliaian Utama: **100 Poin**

#### Framework
- **(10 Poin)** Menggunakan framework CodeIgniter.
- **(10 Poin)** Menggunakan framework Bootstrap.
#### Navigation Bar
- **(5 Poin)** Website memiliki sebuah Navigation Bar/Navbar.
- **(5 Poin)** Navbar menyediakan link menuju halaman tampilan data dan halaman input data.
- **(5 Poin)** Navbar dinamis (Jika user berada di satu halaman, maka link ke halaman tersebut diberi tanda). 
  *Misalnya pada contoh, link ke halaman yang sedang dibuka user di-bold.*
#### Halaman Tampilan Data
- **(10 Poin)** Website dapat menampilkan seluruh data mahasiswa yang ada dalam bentuk tabel.
- **(5 Poin)** Data yang ditampilkan diurutkan berdasarkan nama mahasiswa.
- **(10 Poin)** Website menggunakan konsep Pagination saat menampilkan data (Jumlah data per halaman tidak ditentukan).

#### Halaman Input Data Baru
- **(10 Poin)** Website memiliki satu halaman form yang berisi field *NIM*, *nama*, *Tanggal Lahir*, dan *Jurusan*.
- **(10 Poin)** Form dapat memasukkan nilai ke dalam database.
- **(10 Poin)** Form memiliki field "Fakultas" yang dapat dipilih user, dimana field tersebut mengubah pilihan pada field Jurusan secara dinamis.
- **(5 Poin)** User tidak bisa menekan tombol "Submit" sebelum mengisi seluruh field yang ada.
- **(5 Poin)** Setelah user menekan "Submit", maka Website kembali ke halaman utama dan memberi feedback ke user bahwa data berhasil dimasukkan.
*Misalnya pada contoh, akan keluar kotak berwarna hijau pada bagian atas halaman setelah user memasukkan data*

### Bonus
> Total Penilaian Utama + Bonus: **120 Poin**
- **(5 Poin)** Tidak ada folder user_guide, controller welcome, dan view welcome_message pada website.
- **(5 Poin)** Title Website dinamis.
- **(5 Poin)** Ada logo Unsri pada Navbar.
- **(5 Poin)** Halaman tampilan data terbuka jika pengguna membuka root folder (misal http://localhost/ci/index.php/) 



# File Database

File .SQL berisi struktur database dan beberapa contoh datanya. [**DOWNLOAD DISINI**](https://drive.google.com/file/d/1h1KOmqr_cHJ1855LEx3rQPu3yE_Aat9y/view?usp=sharing)

# Contoh Implementasi Website

Contoh Website dapat dilihat [**DISINI**](https://uasprakweb2017.000webhostapp.com/).

# Form Pengumpulan

Silahkan kumpul file website yang sudah diupload pada cloud/service file-sharing [**DISINI**](https://docs.google.com/forms/d/e/1FAIpQLSf4hhpVxwthKoCNY6s7wTdaRXke71O-5dQIQA7xVK4BsHjtZg/viewform?usp=sf_link).
Jika ada bagian-bagian yang tidak anda kerjakan secara sempurna (hanya setengah jadi, ada bug, dsb), mohon tuliskan dan jelaskan pada kolom yang disediakan pada form.

