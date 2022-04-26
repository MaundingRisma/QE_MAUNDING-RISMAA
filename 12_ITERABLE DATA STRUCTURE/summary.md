
iterable data adalah sekumpulan data yang dapat dilakukan iterasi atau perulangan kepadanya. 
interface dibagi menjadi 3 :
- set 
- list
- deque

1. method pada iterable :
	- ForEach
	- Iterator
		kelas yang memanage iterasi dari suatu iterable(mengelola pada bagian mana kita sudah melakukan iterasi pada bagian iterable dan mengetahui data apa yang berikutnya harus diambil dan juga bagaimana cara mengambilnya)
	- Spliterator

2. collection 
	merupakan kumpulan suatu data yang diletakkan pada tempat yang sama 
	method collection :
	- penambahan 
	- penghapusan data
	- memeriksa isi dari data yang tersedia
	- method - method dari iterable seperti iterator dan spliterator
	- method untuk melihat ukuran dari collection 

	outpunya = true 

3. List
	menyimpan data secara linier. merupakan turunan dari interface collection, list dapat menerima nilai yang sama. method pada list berfungsi untuk memanajemen data yang ada pada list.

	.implementasi dari interface list:
		- abstrack list
		- ArrayList
			menyediakan penyimpanan data yang dinamis, tidak terikat dengan kapasitas penyimpanan data pada list tersebut. data yang disimpan pada array list dapat sebanyak apapun selagi memori pada komputer masi bisa mencukupi.
		- Abstrack Sequencial List
		- Vector
		- LinkedList
		- Stack

