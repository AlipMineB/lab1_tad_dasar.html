# lab1_tad_dasar.html
Persiapan membuka VSCode dengan browser
![image](https://github.com/AlipMineB/lab1_tad_dasar.html/assets/116167509/84e31116-7fbd-4a59-9aba-b87eedd527ed)
kemudian buat file baru dengan nama #lab1_tag_dasar.html# dan tambahkan tag dasar dokumen HTML
![image](https://github.com/AlipMineB/lab1_tad_dasar.html/assets/116167509/d3461762-d617-46c7-8f51-8816106a5f2b)
kemudian selanjutnya, buka file tersebut pada web browser, misalnya #chrome#
![image](https://github.com/AlipMineB/lab1_tad_dasar.html/assets/116167509/1090b4dc-7d79-4158-afc4-525d0feb1c4a)
# 1.Membuat Paragraf
Selanjutnya buatlah beberapa paragraf sederhana seperti berikut
        <!--Ini adalah paragraf pertama-->
        <p align>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman WEb di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML.</p>

        <!--ini adalah paragraf kedua-->
        <p align>Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling mendukung sehungga menjadi satu kesatuan. paragraf dibuat dengan menggunakan tag dasr html.</p>
![image](https://github.com/AlipMineB/lab1_tad_dasar.html/assets/116167509/e8bdca43-8dab-44f1-9279-c583aaa2f046)
Selanjutnya simpan kembali perubahannya, dan lakukan refresh pada web browser, lihat hasilnya.
![image](https://github.com/AlipMineB/lab1_tad_dasar.html/assets/116167509/12da482e-5caf-4da6-88eb-d24b49bfbe8d)
kemudian atur atribut paragraf seperti berikut, dan amati perubahannya 
        <!--Ini adalah paragraf pertama-->
        <p align="centere">Kami sedang belajar HTML dasar, pada matakuliah Pemrograman WEb di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML.</p>

        <!--ini adalah paragraf kedua-->
        <p align="right">Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling mendukung sehungga menjadi satu kesatuan. paragraf dibuat dengan menggunakan tag dasr html.</p>
![image](https://github.com/AlipMineB/lab1_tad_dasar.html/assets/116167509/2e6c041d-22d0-4523-a1ae-e1909395205d)
simpan kembali dan amati perubahannya dengan melakukan refresh pada web browser. selanjutnya silahkan ubah - ubah nilai atributnya (align=justify, left, right, dan center)

align= center dan right 
![image](https://github.com/AlipMineB/lab1_tad_dasar.html/assets/116167509/73d610ef-4fe3-4f22-8ee3-d6ead7d662e5)

align = Justify and left
![image](https://github.com/AlipMineB/lab1_tad_dasar.html/assets/116167509/f60dfda2-aea1-4907-80f4-888b2d25bd2f)

hasilnya
![image](https://github.com/AlipMineB/lab1_tad_dasar.html/assets/116167509/f0d05ce3-d5d2-49be-9c09-da8db3fbca0d)

# 2. Membuat judul
seperti sudah dijelaskan pada materi bahwa judul memiliki 6 level yaitu h1 sampai h6. kemudian tambahkan judul h1 sebelum paragraf pertama dan tambahkan sub judul h2 sebelum paragraf kedua.
        <!--judul paragraf pertama-->
        <h1>Belajar Dasar HTML</h1>
        
        <!--judul paragraf kedua-->
        <h2>Paragraf pada HTML</h2>
![image](https://github.com/AlipMineB/lab1_tad_dasar.html/assets/116167509/131a5931-d5fd-484c-892e-fa5cae4c986d)
simpan perubahannya dan lihat hasilnya dengan melakukan refresh pada browser.
![image](https://github.com/AlipMineB/lab1_tad_dasar.html/assets/116167509/14facb83-8c0c-4396-a2bc-8ecba800c7be)

# 3. Memformat Teks
Lakukan pemformatan teks yang ada pada paragraf yang sudah ada sebelumnya, mengacu kepada penjelasan materi pemformatan teks, sehingga tampilannya seperti berikut.
![image](https://github.com/AlipMineB/lab1_tad_dasar.html/assets/116167509/4beb1775-1ae2-4e7d-9b8d-c6a867214d33)

# Code 
        <!--judul paragraf pertama-->
        <h1>Belajar Dasar HTML</h1>
        <!--Ini adalah paragraf pertama-->
        <p align="justify">Kami sedang belajar <mark>HTML dasar</mark>, pada matakuliah <b>Pemrograman WEb</b> di Prodi <i>Teknik Informatika</i> <u>Universitas Pelita Bangsa</u>. Pelajaran pertama yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML.</p>

# 4. Menyisipkan gambar 

Untuk menyisipkan gmbar, siapkan gambar yang akan disisipkan pada halaman web, kemudian simpan file gambar tersebut satu folder dengan file dokumen html. Atau bisa juga menyisipkan gambar dari website external.
![image](https://github.com/AlipMineB/lab1_tad_dasar.html/assets/116167509/2d0d6a05-c5ab-4862-96a3-0b346d95fa66)
kemudian tambahkan tag img setelah paragraf yang kedua, dengan menambahkan heading 3 sebelumnya.
        <!--sub judul paragraf-->
        <h3>Menambahkan Gambar</h3>
        <!--menambahkan gambar pada dokumen-->
        <img src="Logo_UPB.jpg" tittle="Logo Universitas Pelita Bangsa"> 
![image](https://github.com/AlipMineB/lab1_tad_dasar.html/assets/116167509/daa226f1-111a-4e74-9530-594af194bd72)
Gambar akan ditampilkan apa adanya sesuai dengan ukuran aslinya. Untuk mengatur ukuran gambar, dapat digunakan atribut witdh dan height dengan nilai integer yang disesuaikan.
        <!--sub judul paragraf-->
        <h3>Menambahkan Gambar</h3>
        <!--menambahkan gambar pada dokumen-->
        <img src="Logo_UPB.jpg" width="200" tittle="Logo Universitas Pelita Bangsa">

# 5. Menambahkan Hyperlink
Tambahkan hyperlink pada dokumen sebelum heading 1 seperti berikut.
        <!--menambahkan link navigasi-->
            <nav>
                <a href="lab1_tag_dasar.html">Dasar HTML</a>
                <a href="lab1_halaman2.html">Halaman 2</a>
                <a href="http://www.google.com">Halaman Web Eksternal</a>
            </nav>
            <hr> 
Buat satu file lagi dengan nama lab1_halaman2.html kemudian isi dokumen tersebut dengan tag html dasar dan dengan isi bebas, boleh mengcopy dari halaman sebelumnya.
![image](https://github.com/AlipMineB/lab1_tad_dasar.html/assets/116167509/6252571e-72f8-4bb8-b09f-317fb5c62250)

# Jawab Pertanyaan Berikut
1.Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah error ketika terjadi kesalahan penulisan tag?

2. Apa perbedaan dari tag
dengan tag
, berikan penjelasannya!

3.Apa perbedaan atribut title dan alt pada tag , berikan penjelasannya!

4.Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!

5.Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top, _parent ), apa yang terjadi pada masing-masing nilai antribut tersebut?
# Jawaban
1. ya, kesalahan penulisan tag dalam kode HTML dapat menyebabkan error atau masalah dalam halaman web. Kesalahan tersebut dapat mencakup tag yang tidak ditutup dengan benar, tag yang tidak valid, atau atribut yang salah

2. ya, kesalahan penulisan tag dalam kode HTML dapat menyebabkan error atau masalah dalam halaman web. Kesalahan tersebut dapat mencakup tag yang tidak ditutup dengan benar, tag yang tidak valid, atau atribut yang salah
3.
Atribut alt (Alternative Text):

Atribut alt digunakan untuk memberikan teks alternatif atau deskripsi gambar.
Ini memiliki peran penting dalam aksesibilitas web, karena digunakan oleh pembaca layar untuk membantu pengguna yang memiliki masalah penglihatan memahami konten gambar

Jika gambar tidak dapat ditampilkan (misalnya, jika berkas gambar tidak dapat dimuat), teks alt akan muncul sebagai teks pengganti.

Contoh penggunaan: <img src="gambar.jpg" alt="Sebuah gambar bukit yang indah"> 

Atribut title:

Atribut title digunakan untuk memberikan informasi tambahan atau tooltip ketika pengguna mengarahkan kursor mouse ke gambar.

Ini tidak memiliki dampak pada aksesibilitas web, tetapi dapat memberikan informasi tambahan kepada pengguna tentang gambar tersebut.
Jadi, perbedaan utama adalah bahwa `alt` digunakan untuk memberikan teks alternatif untuk gambar dan penting untuk aksesibilitas, sementara `title` digunakan untuk memberikan informasi tambahan yang muncul sebagai tooltip saat pengguna mengarahkan kursor mouse ke gambar.
Jadi, perbedaan utama adalah bahwa `alt` digunakan untuk memberikan teks alternatif untuk gambar dan penting untuk aksesibilitas, sementara `title` digunakan untuk memberikan informasi tambahan yang muncul sebagai tooltip saat pengguna mengarahkan kursor mouse ke gambar.

4. Untuk mengatur ukuran gambar dalam HTML, dapat menggunakan atribut width (lebar) dan height (tinggi). Agar tampilan gambar tetap proporsional, sebaiknya mengisi hanya salah satu dari kedua atribut tersebut, biasanya width atau height, sementara yang lainnya akan dihitung secara otomatis oleh browser.
      Ini dilakukan karena gambar memiliki rasio aspek (aspect ratio), yang merupakan perbandingan antara lebar dan tingginya. Jika mengisi baik `width` maupun `height`, tanpa memperhatikan rasio aspek gambar, gambar tersebut dapat terlihat terdistorsi atau tidak proporsional.

5. _blank:

Ketika target="_blank" digunakan, tautan akan membuka halaman yang ditautkan dalam tab atau jendela browser baru, terpisah dari halaman asal. Ini berguna ketika Anda ingin menjaga pengguna tetap di halaman asal dan membuka tautan eksternal atau tautan yang tidak ingin menggantikan halaman asal.
_self:

Ini adalah nilai default untuk atribut target. Ketika target="_self" digunakan, tautan akan membuka halaman yang ditautkan di jendela atau tab yang sama di mana halaman asal berada. Ini berarti halaman asal akan digantikan dengan halaman yang baru.
_top:

Ketika target="_top" digunakan, tautan akan membuka halaman yang ditautkan di jendela atau tab paling atas atau paling tinggi dalam tumpukan jendela browser. Jadi, jika halaman asal ada dalam bingkai (frame), tautan akan membuka halaman baru di luar bingkai tersebut.
_parent:

target="_parent" digunakan ketika halaman web memiliki bingkai (frame) yang saling terkait. Ini akan membuka tautan di jendela atau tab yang menggantikan bingkai "induk" yang berisi tautan tersebut.
