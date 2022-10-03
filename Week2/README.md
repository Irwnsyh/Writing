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
