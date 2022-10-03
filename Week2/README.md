# RANGKUMAN WEEK 2
## **Javascript Dasar**
### Scope dan Function
- **Scope** merupakan sebuah konsep dalam flow data variabel.
- Scope terdiri atas 2 macam, yaitu:
  - Global Scope, contoh Global Scope:
    ```global
        let myName = "irwansyah" ; 
        function greeting()
            return myName;
        {
            console.log(myName);
    ```
  - Local Scope, contoh Local:
    ```local
    // Jika variabel "nama" ditempatkan di luar function maka tidak bisa digunakan
    function myFunction() {   
      name = "irwan";   
    }
    ```
- **Blocks** merupakan code yang berada dalam curly braces{}.
  > Conditional, Function, dan Looping menggunakan Bloscks.
- **Function** adalah sebuah code blok dalam sebuah grup untuk menyelesaikan 1 task.
  ```function
  // Membuat Function
  function greeting() {
     return "Hello World";
  };
  // Memanggil Function
  greeting()
  console.log(greeting());
  ```
  
- **Argumen** adalah nilai yang digunakan saat memanggil function.
  > Jumlah dari argumen harus sama dengan jumlah parameternya.
  
- Contoh Argumen:
  ```argumen
  function penambahan(a,b){
   return a + b;
  }
    console.log(penambahan(5,5))
  ```
 
- **Parameter** berfungsi sebagai penerima sebuah pesan dari inputan data yang digunakan untuk melakukan task.
- Contoh Parameter:
  ```parameter
  function calculateArea(width,height){
    console.log(width * height);
  }
  ```
- **Arrow Function** merupakan cara lain untuk menuliskan syntax dengan cara lebih pendek. Contoh penulisannya:
  ```arrow
  const greeting = (a,b) => {
    return a + b;
  }
  ```
### DOM HTML
- **DOM** (Document Object Model) adalah interface yang memungkinkan developer memanipulasi halaman web dari segi struktur, tampilan, dan kontennya.
  > **DOM** merupakan sesuatu yang bisa memanipulasi halaman web HTML 
- Cara memanggil DOM Value yaitu :
  - Memanggil tag HTML berdasarkan ID
  `` console.log(document.getElementByID("header))``
  - Memanggil tag HTML berdasarkan Class Name 
  `` console.log(document.getElementByClassName("text-color-blue"))``
  - Memanggil tag html berdasarkan query selector
  `` console.log(document.querySelector("#header "))`` 
  `` console.log(document.querySelector(".text-color-blue"))``
- Cara memanipulasi content :
  1. Deklarasi varible header sebagai wadah untuk menyimpan tag HTML
  `` let header = document.getElementById("header"); ``
  2. Memanipulasi Content pada Header Content dari pemilik element dengan ID Header dengan text.Content
  `` document.getElementById("header").textContent = "Teks Heading" `` <br />
     Memanipulasi Content didalam sebuah element dengan .innerHTML
  ```
  <ul id= "list"></ul>

  document.getElementById("list").innerHTML = "<li> item1 </li> <li> item2 </li>"
  ```
  - **DOM Events** merupakan object model yang bertugas untuk membantu interaksi user dengan document HTML
- Contoh HTML DOM events
  - Click
  - Scroll
  - Change
  - Focus
  - Hover
  - Submit
  - Blur
- Menangkap Interaksi User
  - Element.addEventListener("event)
  - Element.onevent
- EventListener <br />
  Dengan menggunakan Element.addEventListener("event") dapat menerapkan beberapa hal yaitu :
  - Bisa dihilangkan
  - Bisa ada beberapa event listener yang sama untuk 1 element
  - Memiliki argument tambahan {options}
