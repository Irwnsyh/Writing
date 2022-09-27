# Rangkuman Week 1
## **Unix Command Line**
- ### Command Line Interface (CLI)
Merupakan program yang memungkinkan pengguna mengetik perintah teks yang memerintahkan komputer untuk melakukan tugas tertentu.
- ### Shell
Program yang memungkinkan pengguna mengetik perintah teks yang memerintahkan komputer untuk melakukan tugas tertentu. Dengan kata lain, Shell adalah program yang digunakan untuk berkomunikasi menghubungkan pengguna dengan sistem operasi.
- ### Terminal
User dan komputer akan dihubungkan dengan Terminal, yang dimana terminal adalah wadah/tempat bagi user untuk mengetikan perintah-perintah kepada komputer. Disini juga Shell akan berperan.
- ### File System
Struktur yang mengatur bagaimana cara data disimpan di sistem. Contoh Sistem operasi Windows & Unix-like menyusun file dan direktori menggunakan struktur yang bentuknya mirip tree, yaitu:

![tree](https://user-images.githubusercontent.com/114460269/192463197-4ca199bc-d8be-4344-aedc-d50a32a8e92f.jpg)
- ### Command
  - **pwd** (print working directory), untuk melihat current working directory
  - **dir** (directory), untuk melihat directory
  - **cd** (change directory), untuk pindah directory
  - **ls** (list), untuk melihat isi file di dalam directory
  - **touch**, untuk membuat file directory
  - **cp** (copy), untuk menyalin file directory
  - **mv** (move), untuk memindahkan file directory
  - **rm** (remove), untuk menghapus file directory

  &nbsp;

## **Git & Github**
- ### Git & Github itu apa?
  - **Git**
  <div align="justify">Merupakan sebuah tools bagi para programmer dan developer yang berfungsi sebagai control system untuk menjalankan proyek pengembangan software. Tujuan penggunaan GIT yakni untuk mengelola versi source code program dengan menentukan baris serta kode yang akan ditambahkan atau diganti.
  
  - **Github**
  <div align="justify">Merupakan layanan cloud yang berguna untuk menyimpan dan mengelola sebuah project yang dinamakan repository (repo git). Cara kerja pada GitHub harus terkoneksi pada internet sehingga tidak perlu meng-install sebuah software ke dalam perangkat keras.

### Apa Perbedaan Git & Github?
GIT dan GitHub sebenarnya merupakan dua platform yang didirikan oleh perusahaan dan dengan tujuan yang sama, namun fitur yang dimilikinya berbeda. Berikut ini beberapa perbedaan antara GIT dan GitHub, yaitu:

|**Git**| **Github** |
|--|--|
| Dikelola oleh The Linux Foundation | Diakuisisi oleh Microsoft |
| Diakses secara offline | Diakses secara online |
| Tidak memakai fitur user management |	Menggunakan fitur user management |
| Install software di penyimpanan lokal | Di-host melalui layanan cloud |
|Fokus pada version control dan code sharing | Fokus pada source code hosting yang terpusat |

### Mengapa wajib menggunakan Git & Github?
Alasan utamanya adalah sepandai apapun programmer, tidak akan mampu untuk mengerjakan semuanya sendiri selamanya. Maka dari itu dengan menggunakan Git & Github akan memudahkan programmer untuk bisa bekerja sama dalam sebuah tim. Tujuan besarnya adalah programmer bisa berkolaborasi dengan programmer lainnya dengan mengerjakan proyek yang sama tanpa harus repot copy paste folder aplikasi yang terupdate.

- ### Command di dalam Git & Github
  - <div align="justify">Hal pertama yang sebaiknya Anda lakukan ketika memasang Git adalah menetapkan nama pengguna dan alamat surel. Ini penting, karena setiap commit pada Git menggunakan informasi ini, dan itu dituliskan dan tidak dapat diganti ke dalam commit yang Anda buat:
  > $ git config --global user.name "Irwansyah"
  > $ git config --global user.email "Irwansya@example.com"
