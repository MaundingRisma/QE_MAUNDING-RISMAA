
KIND OF API TESTING
- functionality → test seperti biasanya apakah suatu fitur sudah berfungsi atau belum

- Negative → Error Handling pada fitur tsb

- Load test → Mengtest kekuatan sistem. mampu mengolah berapa banyak trx misal kan

- security → mengetest keamanan sistem

DIFFERENCE BETWEEN API TEST AND UNIT TEST 
	** UNIT TEST
		- dilakukan oleh developer
		- fungsi-fungsi terpisah
		- developer bisa mengakses source code
		- hanya dasar functionality yang di test
		- scopenya terbatas
		- biasanya dilakukan sebelum build

	** API TEST
		- tester perform it
		- end to end
		- tidak bisa mengakses source code
		- hanya fungsi API saja
		- semua function issue 
		- scopenya lebih luas
		- dilakukan setelah build 

	TEST CASE FOR API TESTING
		- mendapatkan balikan yang sesuai dengan inputan
		- apakah memberikan balikan atau tidak
		- apakah mengganggu fitur yang lain atau tidak
		- update struktur data
		- memodifikasi data yang ada 

TYPE OF OUTPUT OF an API 
- bisa berbentuk apa saja, pada umumnya JSON atau XML
- status balikan apakah passed atau fail
- memanggil fungsi API lain