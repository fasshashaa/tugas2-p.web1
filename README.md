
# LAPORAN PRAKTIKUM PEMROGRAMAN WEB 1

Nama : Fassha Fanny Purwanto(230202035) 
Kelas : TI-1B

## HTML 
HTML merupakan singkatan dari Hypertext Markup Language yang merupakan bahasa markup standar untuk halaman web.
1) HTML home / basic 
Didalam HTML terdapat beberapa elemen penyusun : !DOCTYPE html untuk mendefinisikan dokumen, html elemen akar halaman html,head  berisi informasi meta, title menentukan judul untuk halaman HTML (yang ditampilkan di bilah judul browser atau di tab halaman), body mendefinisikan badan dokumen, h1 mendefinisikan judul besar, p mendefinisikan paragraf.

2. HTML Attribute, Semua elemen HTML memiliki aribut untuk memberikan informasi tambahan  tentang elemen. Atribut biasanya datang dalam pasangan nama/nilai seperti: name=”value”.
Beberapa atribut HTML : Atribut href dengan tag a untuk mendefinisikan hyperlink dan atribut href menentukan URL halaman link yang dituju Atribut src dengan tag img digunakan unuk menyematkan gambar dihalaman HTML dan Aribut src menentukan jalur ke gambar yang akan ditampilkan, Atribut style yang digunakan untuk menambahkan gaya kesuatu elemen seperti warna, ukuran dll.

3. Pemformatan teks html, di html terdapat beberapa eemen unuk mendefinisikan teks dengan arti khusus. Beberapa elemen pemformatan HTML diantaranya ; b- Teks tebal, strong- Teks penting, i- Teks miring, em- Teks yang ditekankan, mark- Teks yang ditandai, small- Teks lebih kecil, del - Teks yang dihapus, ins - Teks yang disisipkan, sub - Teks subskrip, sup - Teks superskrip.

4. Favicon adalah gambar kecil yang ditampilkan di sebelah judul halaman di tab browser. Utuk menambahkan favicon, siapkan gambaar dan etakkan di folder yang sama dengan file. Selanjutnya bisa tambahkan perintah :
link rel="icon" type="image/x-icon" href="/images/favicon.ico"

setelah title elemen untuk menampikan favicon.

5. Tabel HTML memungkinkan pengembang web untuk mengatur data ke dalam baris dan kolom. Setiap sel tabel ditentukan oleh a td dan /td tag. td singkatan dari table data. Segala sesuatu di antara td dan /td merupakan konten sel tabel. Setiap baris tabel dimulai dengan a tr dan diakhiri dengan /tr tag.  tr singkatan dari table row. th singkatan dari table header.

## Program basic HTML


![alt text](?raw=true)



## CSS
CSS merupakan singkatan dari Cascading Style Sheets. CSS digunakan untuk menentukan gaya halama termasuk desain, tata letak, dan variasi tampilan untuk berbagai perangkat dan ukuran layar. 
1)	CSS syntax
Aturan css terdiri dari selector dan declaration. Selector menunjuk ke elemen HTML yang ingin anda berikan gaya. Declaration berisi satu atau lebih deklarasi yang dipisahkan oleh titik koma. Setiap deklarasi menyertakan nama properti CSS dan nilainya, dipisahkan oleh titik dua. Beberapa deklarasi CSS dipisahkan dengan titik koma, dan blok deklarasi diapit oleh kurung kurawal.

2.	CSS Selectors
Selector CSS digunakan untuk "menemukan" (atau memilih) elemen HTML yang ingin dihias/diberi gaya.
 Terdapat 5 kategori selector :

a.	Simple selector (pilih elemen berdasarkan nama, id, kelas)

b.	Combinator selector (memilih elemen berdasarkan hubungan tertentu di antara elemen tersebut)

c.	Pseudo-class selectors (memilih elemen berdasarkan keadaan tertentu)

d.	Pseudo-elements selectors (memilih dan memberi gaya pada bagian elemen)

e.	Attribute selectors (memilih elemen berdasarkan atribut atau nilai atribut)

3. 	CSS Background
CSS background digunakan untuk menambahkan efek latar belakang pada elemen. 

a.	Background-color, untuk menentukan warna latar beakang suatu elemen

b.	Background-image, untukmenentukan gambar sebagai latar belakang suatu elemen

c.	Background-repeat, untuk pengulangan latar belakng  gambar secara vertical maupun horizontal

d.	Background-attachment, menentukan apakah latar belakang harus digulir atau tidak.

4.	CSS Borders
CSS Borders berfungsi untuk meentukan gaya, lebar, dan warna batas elemen.
Nilai nilai CSS border :

a.	dotted- Mendefinisikan batas titik-titik

b.	dashed- Mendefinisikan batas putus-putus

c.	solid- Mendefinisikan batas yang solid

d.	double- Mendefinisikan perbatasan ganda

e.	groove- Mendefinisikan batas beralur 3D. Efeknya bergantung pada nilai warna batas

f.	ridge- Mendefinisikan batas bergerigi 3D. Efeknya bergantung pada nilai warna batas

5.	CSS List
Dalam HTML dan CSS, ada dua tipe utama list: Daftar tidak berurutan (ul) - item daftar ditandai dengan poin, daftar terurut (ol) - item daftar ditandai dengan angka atau huruf


![alt text](?raw=true)


## JavaScript
JavaScript adalah salah satu dari Bahasa lainnya yang harus diketahui untuk mengembangkan web. 
Dalam HTML, kode JavaScript disisipkan di antara tag script dan /script. 

1)	Javascript Output
JavaScript dapat "menampilkan" data dengan berbagai cara:

a.	Menulis ke dalam elemen HTML, menggunakan innerHTML.

b.	Menulis ke dalam output HTML menggunakan document.write().

c.	Menulis ke dalam kotak peringatan, menggunakan window.alert().

d.	Menulis ke konsol browser, menggunakan console.log().

e.	Memanggil window.print() untuk mencetak konten jendela saat ini.

2.	Javacript Operators
Operator Javascript digunakan untuk melakukan berbagai jenis perhitungan matematis dan logis.
Contoh:
-	Operator sama dengan = memberikan nilai
-	Operator Penambahan + menambahkan nilai
-	Operator Perkalian * mengalikan nilai
-	Operator Perbandingan > membandingkan nilai

3. Operator Perbandingan dan Logika digunakan untuk menguji true atau false. Operator perbandingan digunakan dalam pernyataan logika untuk menentukan persamaan atau perbedaan antara variabel atau nilai. Operator logika digunakan untuk menentukan logika antar variabel atau nilai. Operator kondisional yang memberikan nilai pada variabel berdasarkan beberapa kondisi.
Membandingkan data dari tipe yang berbeda mungkin memberikan hasil yang tidak diharapkan.
Saat membandingkan string dengan angka, JavaScript akan mengubah string tersebut menjadi angka saat melakukan perbandingan. String kosong dikonversi menjadi 0. String non-numerik dikonversi menjadi NaN yang selalu false.

4.	Javascript if else
Pernyataan kondisional dalam javascript :

•	Gunakan if untuk menentukan blok kode yang akan dieksekusi, jika kondisi yang ditentukan benar

•	Gunakan else untuk menentukan blok kode yang akan dieksekusi, jika kondisi yang sama salah

•	Gunakan else if untuk menentukan kondisi baru yang akan diuji, jika kondisi pertama salah

•	Gunakan switch untuk menentukan banyak blok kode alternatif yang akan dieksekusi

5.	Javascript switch
Switch digunakan untuk melakukan tindakan berbeda berdasarkan kondisi berbeda. 
 Cara kerjanya:

•	Ekspresi switch dievaluasi satu kali.

•	Nilai ekspresi dibandingkan dengan nilai setiap kasus.

•	Jika ada kecocokan, blok kode terkait akan dieksekusi.

•	Jika tidak ada kecocokan, blok kode default dijalankan.

6.	Javascript loop
Loop dapat mengeksekusi blok kode beberapa kali. 
JavaScript mendukung berbagai jenis loop:

•	for- mengulang blok kode beberapa kali

•	for/in- menelusuri properti suatu objek

•	for/of- mengulang nilai objek yang dapat diubah

•	while- mengulang blok kode selama kondisi yang ditentukan benar

•	do/while- juga mengulang blok kode selama kondisi yang ditentukan benar


![alt text](?raw=true)
