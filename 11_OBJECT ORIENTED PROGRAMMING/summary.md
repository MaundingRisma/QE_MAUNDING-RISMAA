Materi yang dipelajari 

1. Class adalah blueprint, prototype atau cetakan untuk membuat Object. Class berisikan deklarasi semua properties dan functions yang dimiliki oleh Object Setiap Object dibuat dari Class Dan sebuah Class bisa membuat Object sebanyak-banyaknya.

2. Object adalah data yang berisi field / properties / attributes dan method / function / behavior.
object dibagi menjadi 3 :
	- Declaration : mendeklarasikan nama sebuah objek
	- Instantiation : memerlukan sebuah perintah new untuk menciptakan objek
	- Initialization : inisialisasi dari sebuah objek setelah perintah new

3. Method 
	Fungsi dan Prosedure di dalam pemrograman java disebut sebagai method. Method/Metode di dalam kelas adalah block statement yang memiliki nama dan bisa dieksekusi dengan memanggilnya

4. Acces Modifier
	Public bisa kita sebut sebagai modifier global.

	Default berarti penulisan kodenya tanpa atribut modifier. Modifier default bisa diakses selama masih dalam satu package

	Private akan membatasi akses hanya di dalam class

	Protected bisa diakses selama masih dalam satu package, perbedaan dengan default, protected bisa diakses selama masih dalam satu package dengan syarat kelas yang hendak mengakses, merupakan kelas turunannya

5. Inheritance
	Dalam artian, kita bisa membuat class Parent dan class Child.Class Child, hanya bisa punya satu class Parent, namun satu class Parent bisa punya banyak class Child. Saat sebuah class diturunkan, maka semua field dan method yang ada di class Parent, secara otomatis akan dimiliki oleh class Child. Untuk melakukan pewarisan, di class child, kita harus menggunakan kata kunci extends lalu diikuti dengan nama class parent nya