# Rangkuman Materi Javascript lanjutan

### 1. Closure
Closure adalah fungsi di dalam fungsi lain, artinya suatu fungsi sebagai outer function yang di dalamnya terdapat inner function yang dapat mengakses variabel yang dimiliki oleh fungsi luar/outer, juga mengakses variabel lokal dan variabel global. Berikut ini contoh sederhana closure:

![closure](https://user-images.githubusercontent.com/104087436/193445605-5112430d-4e75-4945-835b-54bcad150e54.png)

Pada contoh diatas, `function myNama()` sebagai outer function yang memiliki variabel lokal didalamnya dan juga di dalam fungsi ini terdapat function `tampilNama()` sebagai inner fungsi yang menjalankan `console.log(nama)` lalu dilakukan pemanggilan function `tampilNama` dan juga pemanggilan function `myNama.` Pada kasus ini, fungsi `tampilNama` memiliki akses ke variabel nama sehingga disebut sebagai closure dikarenakan memerlukan variabel nama yang terdapat di parent variabel. Ketika program dijalankan maka akan ditampilkan hasilnya yaitu `Jane.`
Untuk lebih memahami mengenai closure dapat dilihat dari referensi berikut [Klik disini](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Closures).

### 2. Immediately Invoked Function Expression

### 3. First-class function

### 4. Higher-order function

### 5. Execution Context

### 6. Execution Stack

### 7.  Event Loop
