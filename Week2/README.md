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
      name = "Bakso";   
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
