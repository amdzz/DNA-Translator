# DNA-Translator
UAS PBO Soal 6
Soal : Terjemahan DNA menggunakan python: Dengan menggunakan rumus python ini, kita dapat menerjemahkan DNA menjadi RNA dan kemudian menjadi protein. Ini membantu untuk mengubah urutan DNA tertentu menjadi protein yang setara.

# Tentang Program
Menggunakan program ini, pengguna dapat menginput urutan DNA (contoh: TACGGCCCATATATT) dan program akan menerjemahkan urutan DNA tersebut menjadi sebuah urutan RNA sekaligus urutan asam amino(protein) yang setara. RNA dan protein yang setara tentu saja didapat melalui tabel kodon yang banyak tersedia. Program ini dapat membantu pengguna dalam proses transkripsi DNA ke RNA serta translasi dari RNA ke asam amino secara lebih efektif dan lebih mudah. Program ini juga dapat menerima input berupa huruf non kapital (contoh: tacggcccatatatt) karena program akan secara otomatis mengkonversinya menjadi huruf besar setelah diinputkan. selain itu, sesuai dengan tabel kodon dan translasi RNA ke asam amino, program juga dapat mendeteksi jika ada kodon stop dalam urutan yang dimasukkan pengguna. Jadi, program akan otomatis berhenti melakukan translasi ketika bertemu dengan kodon stop.

# Contoh Luaran

![My Image](Media/1412.png)

### Contoh Luaran Ketika Terdapat Kodon Stop

![My Image](Media/stop.png)

# Metode Program
Program tersebut dibuat menggunakan pendekatan OOP (Object-oriented Programming) atau pemrograman berbasis objek. Dengan menggunakan metode OOP, dapat memudahkakn untuk mengorganisir dan mengelompokkan kode ke dalam kelas dan objek yang memiliki properti dan metode terkait. Selain itu pendekatan melalui OOP juga membuat program mudah dibaca dan dipahami sehingga sangat memudahkan dokumentasi dari program. OOP juga membuat program lebih mudah untuk dikembangkan serta dimodifikasi, karena method dan kelasnya memiliki masing-masing fungsi yang jelas. Hal tersebut juga membantu dalam pemeliharaan program, bila ditemukan kesalahan maka dapat mudah ditemukan karena strukturnya yang rapi.

# Struktur Program
Program DNA Translator terdiri dari 1 kelas __DNATranslator__ dan 3 method, salah satu dari methodnya adalah __init__ yang merupakn konstruktor dari kelas. Kemudian terdapat method __transkrip()__ yang berisi proses untuk melakukan transkripsi dari DNA ke RNA, dimana huruf T pada DNA diganti menjadi huruf U. Selanjutnya terdapat method __translasi()__ yang berisi implementasi dari tabel kodon dalam bentuk dictionary sebagai acuan untuk melakukan proses translasi, juga disinilah terdapat perulangan untuk melakukan translasi sekaligus mendeteksi kodon stop. Terakhir, terdapat input untuk menampung input pengguna serta pembentukan objek translator dari kelas __DNATranslator__ dan dua objek lain untuk melakukan proses transkripsi dan translasi. Hasilnya kemudian dicetak menggunakan print.


#### GROUP 11
#### INFORMATIKA B
