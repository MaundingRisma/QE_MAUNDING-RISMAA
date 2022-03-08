poin yang dipelajari :

1. linux coomand adalah sebuah utinitas dari sistem aplikasi Linux. semua tugas dasar dapat dijalnankan dengan mennunakan linux command. command dijalankan di terminal linux. terminal merupakan antarmuka baris perintah untuk berinteraksi dengan sistem. linux command sensitif terhadap huruf besar maupun huruf kecil. 
kelebihan dari command line :
1. less resource :
	command line ringan digunakan sehingga tidak mengharuskan komputer untuk memiliki spesifikasi yang tinggi bila ingin menggunakan command line.

2. repetitive task friendly
	dapat menyimpan skrip dalam tugas yang sama berulang kali.

3. powerful 
	tidak menggunakan akses memori terlalu banyak

>> struktur command linux :
	-ls berfungssi untuk menampliklan semua file pada directory kerja namun pada praktiknya command tanpa options dan parameters tidak berguna. tim kita membutuhkan daftar file dari direktori tertentu pada kondisi yang lebih komplex  pada options dan parameter. 

 contoh :
  ls-a command ini  menunjukkan file dimulai dari titik atau yang tersembunyi. 

 >> contoh basic commands :
 	cal berfungsi untuk menmapilkan calender 
 	date berfungsi untuk menampilkan tanggal dan zona waktu pada OS pengguna 
 	etc. 

 >> file system commands
 	touch merupakan command linux  untuk membuat file baru yang kosong, melalui baris perintah linux. seperti contoh touch /home/username/document/web.html

 	cat adalah salah satu perintah dasar dari sistem operasi linux yang paling sering digunakan perintah ini berfungsi untuk membuat daftra konten pada standar output 
 	contoh cat file.txt

 	cp berfungsi untuk menyaring file dari direktory saat ini ke directory yang berbeda.

 	mv berfungsi untuk memindahkan file meskipun bisa digunakan untuk mengganit atau mengubah nama file. argumen pada mv harus sama dengan argumen pada perintah cp.mv, nama file dan directory tujuan. contohnya mv file.txt/in/username/documents

 	rm berfungsi untuk menghapus direktori beserta isinya. harus mengecek kita berada pada directory mana saat ini. jika command dijalankan semua akan terhapus dan tidak  bisa di kembalikan 

 	mkdir berfungsi untuk membuat directory baru 

 	rmdir berfungsi untuk menghapus directory namun rmdir ini hanya untuk menghapus direktori yang kosong saja.  

 	cd berfungsi untuk menjelajahi file dan directory linux.

 	pwd berfungsi untuk mencari path dari directory yang digunakan saat ini.

>> process control commands 
	top --> command top akan menampilkan daftar proses yang sedang berlangsung dan seberapa bayak ruang cpu yang digunakan oleh top tersebut. 

	clear --> command ini berfungsi untuk membersihkan terminal jika didalamnya sudah banya sekali terdapat commands. 

	history -->  untuk mengecek kembali command yang sudah ditambahkan sebelumnya. 

>> Utilities prograns commands 
	ls --> menampilkan semua file di directory kerja
	which --> command yang digunakan untuk mencari file yang dapat di eksekusi terkait dengan file yang diberikan. 

	sudo --> berfungsi menjalankan task yang memerlukan hak akses atau permission administratif

	find --> berfungsi untuk mencari file dan directory, command find lebih ditujukkan untuk file yang berlokasi dalam directory yang diberikan. 

>> File acces permission 
	chmod --> perintah dasar linux lainnya digunakan untuk membaca, menulis dan menjalankan permission dari file dan directory.

	chown --> untuk mengubah atau mentransfer kepemilikan file ke username. 


>> Shell script :
	merupakan sebuah bahasa pemrograman yang disusun berdasarkan command-command shell.

	shell merupakan program yang berfungsi sebagai jembatan antara user dan kernel. 


