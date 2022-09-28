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

### Apa Saja Command di dalam Git & Github?
- <div align="justify"> Hal pertama yang sebaiknya Anda lakukan ketika memasang Git adalah menetapkan nama pengguna dan alamat surel. Ini penting, karena setiap commit pada Git menggunakan informasi ini, dan itu dituliskan dan tidak dapat diganti ke dalam commit yang Anda buat:   
```
    $ git config --global user.name "irwansyah"
    $ git config --global user.email "irwnsyh0812@gmail.com"
```
 
- <div align="justify"> Ketika ingin memeriksa pengaturan, Kita dapat menggunakan perintah git config --list:
```
    $ git config --list
    pack.packsizelimit=2g
    diff.astextplain.textconv=astextplain
    filter.lfs.clean=git-lfs clean -- %f
    filter.lfs.smudge=git-lfs smudge -- %f
    filter.lfs.process=git-lfs filter-process
    filter.lfs.required=true
    http.sslbackend=openssl
    http.sslcainfo=C:/Program Files/Git/mingw32/ssl/certs/ca-bundle.crt
    core.autocrlf=true
    core.fscache=true
    core.symlinks=false
    pull.rebase=false
    init.defaultbranch=master
    user.name=irwansyah
    user.email=irwnnsyh0812@gmail.com
```
    
- git init <nama_proyek>, digunakan untuk membuat repository di file lokal.
```
    $ git init project1
```
    
- git Status digunakan untuk melihat apakah terjadi perubahan atau tidak pada Git 
- git add untuk menambah file baru/file yang telah diubah pada Git  
- git remote menghubungkan remote repository dengan project local yang telah kita buat direktorinya 
- git commit -m "commit message" digunakan untuk menyimpan perubahan pada Git
- git push -u origin master digunakan untuk mengirimkan/perubahan file ke remote repository 
- git branch -b [nama branch] digunakan untuk membuat branch baru
- git checkout digunakan untuk berpindah branch
- git merge digunakan untuk menggabungkan branch cabang ke branch master ( git merge origin/(nama branch))
    
    &nbsp;
    
## **HTML**
### Definisi
Hypertext Markup Language (**HTML**) adalah suatu bahasa yang menggunakan tanda-tanda tertentu (tag) untuk menyatakan kode-kode yang ditafsirkan pada web agar konten halamannya dapat ditampilkan dengan benar.

### Tools Pendukung HTML
- Tools yang dibutuhkan untuk untuk membuat HTML yaitu web browser dan code editor.
- Kemudian Visual Studio Code juga diperlukan, VScode merupakan salah satu code editor yang dibuat oleh Misrosoft
    
### Kerangka HTML
HTML memiliki kerangka seperti syxntax berikut ini:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Hello World</title>
    <link href="style.css" type="text/css" rel="stylesheet"/>
</head>
    <body>
        <div>
            <h1 class="header">Hello World!!!</h1>
            <p>Apa Kabar Dunia?</p>
        </div>
    </body>
</html>>
```
    
### Tag HTML
Tag adalah sebauh penanda awalan dan akhiran dari sebuah elemen di HTML. Tag dibuat dengan kurung siku (<...>), lalu di dalamnya berisi nama tag dan kadang juga ditambahkan dengan atribut.
Tag selalu ditulis berpasangan. Ada tag pembuka dan ada tag penutupnya. Namun, ada juga beberapa tag yang tidak memiliki pasangan penutup. Tag penutup ditulis dengan menambahkan garis miring (/) di depan nama tag.
Contoh tag HTML:
- Tag untuk membuat tulisan tebal dan miring
```
    <b>Tebal</b> <i>Miring</i>
```
- Tag HTML Untuk Membuat tulisan dengan link
```
    <a href="">Hello World!!!</a>
```
- Tag Untuk Membuat Daftar/List
    - Ordered List

      ```html
      <ol>
        Kelompok
        <li>Kelompok1</li>
        <li>Kelompok2</li>
        <li>Kelompok3</li>
      </ol>
      ```

    - Unordered List

      ```html
      <ul>
        Kelompok
        <li>Kelompok1</li>
        <li>Kelompok2</li>
        <li>Kelompok3</li>
      </ul>
      ```

- Tag HTML Untuk Menampilkan gambar
```
    <img src="https://bit.ly/2FKluzq" alt="Si Kucing"></img>
```
- Semantic HTML
Yaitu menggunakan elemen HTML sesuai dengan kebutuhan konten. Contoh yaitu header, footer, nav, section, aside, dll.
```
    <body>

  <header>
    <h1>My Jurnal</h1>
  </header>

  <nav>
    <a href="#">Home</a> |
    <a href="#">About</a> |
    <a href="#">Contact</a>
  </nav>

  <article>
    <h1>Welcome To My Jurnal</h1>
    <p>Selamat Datang di Jurnal Saya. 
    </p>
  </article>

  <footer>
    Copyright &copy; 2022 by Irwansyah
  </footer>

</body>
```
- Deployment HTML
Deploy adalah sebuah proses untuk menyebarkan aplikasi yang sudah kita kerjakan supaya bisa digunakan oleh orang-orang. Jika aplikasi kita HTML atau Web App kita perlu mendeploy ke server. Untuk melakukan hal tersebut kita bisa menggunakan layanan yang bernama Netlify.
    
  &nbsp;

## **CSS**
- ### Definisi
CSS adalah singkatan dari cascading style sheets, yaitu bahasa yang digunakan untuk menentukan tampilan dan format halaman website. Dengan CSS, Anda bisa mengatur jenis font, warna tulisan, dan latar belakang halaman.
- ### Syntax Dasar CSS
Adalah syntax yang digunakan untuk menunjuk atau memilih HTML element mana yang ingin diberi style (dihias). CSS syntax terdiri dari selector, property, dan value.
Contoh dari syntax CSS, yaitu:
```
    p {
      color: red;
    }
```
Penjelasan :

  - p

    Adalah sebuah selector berupa element HTML yang akan diubah

  - color

    <div align="justify">Adalah sebuah properti berupa bagian mana dari element HTML yang akan diubah. Contoh diatas kita akan mengubah warna dari teks yang ada di element p

  - red

    Adalah value yaitu nilai/hiasan berupa warna merah
      
- ### Styling CSS pada sebuah halaman HTML 

  1. Inline Styles

     Kita menambahkann CSS langsung pada atribut HTML

     ```html
     <p style="color:red">Tulisan ini berwarna merah</p>
     ```

  2. Internal CSS

     Kita menggunakan element/tag `<style>` untuk menyisipkan kode CSS. element/tag `<style>` diletakkan di dalam element `<head>`

     ```html
     <!DOCTYPE html>
     <html>
       <head>
         <title>Website Pertamaku</title>
         <style>
           body {
             background-color: yellow;
           }
           h1 {
             color: blue;
           }
           p {
             color: red;
           }
         </style>
       </head>
       <body>
         <h1>Website Pertamaku</h1>
         <p>Selamat Datang</p>
       </body>
     </html>
     ```

  3. Eksternal CSS

     <div align="justify">Kita akan menyisipkan kode CSS dengan cara membuat file CSS terpisah, dan lalu menyambungkannya dengan file HTML dengan menggunakan element <link>. Element <link> tersebut diletakkan di dalam element <head>

     Contoh:

     <div align="justify">Kita memiliki dua file: index.html untuk file HTML-nya dan styles.css untuk file CSS-nya.

     ```html
     <!-- File index.html -->

     <!DOCTYPE html>
     <html>
       <head>
         <title>Website Pertamaku</title>
         <link rel="stylesheet" href="styles.css" />
       </head>
       <body>
         <h1>Website Pertamaku</h1>
         <p>Selamat Datang</p>
       </body>
     </html>
     ```

     ```css
     /* File styles.css */

     body {
       background-color: pink;
     }
     h1 {
       color: blue;
     }
     p {
       color: black;
     }
     ```

- ### Responsive Web Design
Adalah pendekatan untuk pembuatan halaman web yang memanfaatkan tata letak yang fleksibel, gambar yang fleksibel dan kueri media pada style sheet. Keuntungan aplikasi web yang menerapkan responsive adalah informasi yang ditampilkan pada website  dapat disampaikan dan diterima oleh pengunjung dengan baik, tanpa kehilangan sebagian informasi dan terlepas diakses dari perangkat mobile apapun. Cara untuk mengatur layout ini juga biasa disebut **Flexbox**.

  &nbsp;

## **Algoritma and Pseudocode**
- Algoritma adalah deskripsi berupa tahapan-tahapan yang logis untuk mnyelesaikan suatu masalah
- Algoritma berfungsi untuk menyelesaikan masalah secara tersetruktur
- Kualitas suatu algoritma :
  - Input & output harus jelas/ didefinisikan terlebih dahulu dengan tepat
  - Setiap tahapan harus benar -benar selesai dan tidak ambigu
  - Algoritma seharusnya tidak mengandung suatu code pada bahasa pemrograman tertentu.
  - Algoritma harus dibuat agar dapat digunakan dalam bahasa pemrograman apapun
- Kenapa harus mempelajari algotima :
  - Pemrograman terdiri atas algoritma dan struktur data
  - Struktur data digunakan untuk mngelola sebuah data
  - Algoritma menyelesaikan suatu permsalahan mnggunakan sebuah data tersebut
- Contoh Algoritma 
```
Input 1 = 10
Input 2 = 5
Output = Input 1 + Input 2
Print ("Result", output)
```
- Pseudocode merupakan tools yang digunakan untuk menulis algoritma 
- Panduan menulis pseudocode :
  - Huruf kapital digunakan untuk menulis perintah
  - 1 statement hanya terdiri dari 1 baris
  - Menggunakan indentasi
  - Harus bersifat spesifik dan simple
- Contoh Pseudocode
```
Deklarasi 
Jam, Detik 
INPUT jam 
	  Convert Jam ke Detik (*3600)
DISPLAY result
```
- Jenis Pseudocode :
  - Procedural : cara berpikir runut 
  - Conditional: jika dibutuhkan suatu percabangan masalah (if else)
  - Looping    : sebuah perintah yg diulang-ulang
  - Recursive  : sebuah perintah yang memanggil method/function didalam sebuah function

  &nbsp;

## **JavaScript Dasar**
### JavaScript Introduction
- **JavaScript** merupakan bahasa pemograman yang berguna untuk membuat interaksi pada website.
- Menjalankan javascript, yaitu melalui berbagai browser. Namun mozilla dan google chrome merupakan browser yang paling umum digunakan.
- JavaScript juga biasanya dikenal dengan Syntax
	> Syntax adalah sebuah aturan yang digunakan untuk menulis kalimat agar mampu dimengerti oleh bahasa pemrograman. Dalam pembuatannya, seluruh aturan syntax harus terpenuhi.
