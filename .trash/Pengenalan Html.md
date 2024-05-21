
##### Pertemuan 4
# Materi HTML    

teks editor yang digunakan ialah **Visual Studio Code** versi 5, disini kita dapat mengerjakan html, css dan java script.
## contoh program

Kode program :
```html
<!DOCTYPE html>
 <html>
   <head>
     <title>ini adalah judul</title>
   </head>
   <body>
     <P>ini adalah teks </p>
   </body>
 </html>
```

Hasil Program :
![Gambar 18](Aset/IMG4/IMG4_(1).jpg)

## penjelasan program
- `<>` disebut sebagai *tag* dalam program, dan setiap *tag* memiliki fungsinya masing masing.
- "`<>`" ialah tag pembuka dan "`</ >`" ialah tag penutup.
- `<!DOCTYPE html>` menunjukkan bahwa html yang digunakan ialah versi ke-*5*.
- ==`<html>`== berfungsi untuk menyusun dokumen html.
- ==`<head>`== ialah tag untuk menunjukkan kepala pada website.
- `<title>`untuk membuat judul pada website.
- ==`<body>`== ialah tag untuk menunjukkan bada dari website.

# Anatomi elemen Html
disini kita akan membedah anatomi elemen pada html.

## hyperlink pada html
didalam html terdapat tag untuk melakukan hyperlink, berikut contoh penggunaannya :
==`<a href="https://www.isntagram.com/">Login Instagram</a>`==

Kode Program : 
```html
<!DOCTYPE html>
 <html>
   <head>
     <title>ini adalah judul</title>
   </head>
   <body>
     <P> untuk login ke Instagram klik link dibawah ini</p>
     <a href="https://www.instagram.com/">Login Instagram</a>
   </body>
 </html>
```

Hasil Program :
![Gambar 2](Aset/IMG4/IMG4_(2).jpg)

## penjelasan program 
- `<a href="https://www.instagram.com/">` merupakan tag pembuka.
- `href` merupakan *nama atribut*.
- `"https://www.instagram.com/"` merupakan *nilai atribut*.
- ==Login Instagram== merupakan *nama link*.
- `</a>` merupakan tag penutup.
- terdapat juga *tag* yang tidak memerlukan *tag penutup*, contohnya seperti `<br>`.
- `<h>` ialah teks heading yang memiliki 6 tingkat sesuai ketebalan dan ukurannya.
- `<p>` ialah teks untuk membuat paragraf.
- `<b>` ialah tag untuk mempertebal teks.
- `<u>` ialah tag untuk menggaris bawahi teks.
- `<i>` ialah tag untuk memiringkan teks.
- `<br>` ialah tag untuk membuat barus baru.




# Paragraf dan Heading
Berikut ialah penjelasan dari contoh program "Paragraf" dan "Heading"

## Penjelasan Paragraf 
Kode Program :
![Gambar 3](Aset/IMG4/IMG4_(3).jpg)

Hasil Program :
![Gambar 4](Aset/IMG4/IMG4_(4).jpg)


Penjelasan Program :
Program ini berfokus pada penjelasan mengenai tag  `<p>` tag ini berfungsi untuk membuat paragraf baru, dan tag ini tidak memerlukan `<br>` untuk membuat baris baru.


## Penjelasan Heading
Kode Program :
![Gambar 5](Aset/IMG4/IMG4_(5).jpg)

Hasil Program : 
![Gambar 6](Aset/IMG4/IMG4_(6).jpg)

Penjelasan Program : 
Program ini berfokus pada penjelasan tag `<h>` yang berfungsi untuk membuat heading (judul), dan memiliki 6 tingkatan mulai dari `<h1>` sampai `<h6>` semakin rendah angkanya semakin besar juga ukuran fontnya.


##  elemen pada tag heading
untuk tag `<h>`terdapat elemen yaitu "*align*" yang dapat mengubah perataan teks sesuai dengan nilai elemennya contoh nya ialah seperti dibawah ini :
Kode Program :
![Gambar 7](Aset/IMG4/IMG4_(7).jpg)

Hasil Program :
![Gambar 8](Aset/IMG5/IMG5_(1).jpg)
kesimpulan : 
kesimpulannya ialah tag `<p>`memilki atribut tag yaitu "*align*" yang memiliki fungsi untuk perataan teks pada paragraf yang sesuai nilai atribut, dan terdapat 4 nilai atribut dari "*align*" yaitu :
- left (rata kiri)
- right (rata kanan)
- center (rata tengah)
- justify (rata kiri kanan)






##### Pertemuan 5
# Tag List
dalam html ada sebuah tag yang dapat membantu kita dalam ==membuat list dengan menggunakan tag `<ul>` dan tag `<ol>`==tag ini memiliki fungsi yang sama yaitu membuat list namun memiliki perbedaan yaitu tag `<ul>` atau "*unordered list*"membuat list yang tidak beraturan, sedangkan `<ol>`atau "*ordered list*" membuat list yang beraturan. contohnya ialah seperti berikut :
Kode Program :
```html
<!DOCTYPE html>
<html>
<head>
 <title> ini judul</title>
</head>
<body>
 <h4>peralatn XI RPL 1</h4>
 <ul>
  <li>Spidol</li>
  <li>Penghapus</li>
  <li>Kipas</li>
  <li>Buku Bacaan</li>
 </ul>
 <ol>
  <li>NurRahmat Ramadhan</li>
  <li>Abd rahman</li>
  <li>Fachri Ramadhan</li>
 </ol>
</body>
</html>
```

Hasil Program :
![Gambar 9](Aset/IMG5/IMG5_(2).jpg)



# Menambah Komentar
untuk membuat komentar yang tidak dapat di terlihat di browser dan hanya dapat di baca oleh programmer ==dengan cara `<!--tulis komentarmu-->`== contohnya seperti dibawah ini :
Kode program :
```html
<!DOCTYPE hmtl>
<html>
<head>
 <title></title>
</head>
<body>
 <!--Ini adalah sebuah komentar dan tidak ditampilkan pada browser-->
 <p>Ini adalah sebuah teks dan akan ditampilkan pada browser</p>
</body>
</html>
```

Hasil Program :
![Gambar 10](Aset/IMG5/IMG5_(3).jpg)
dengan menuliskan komentar dapat membantu program untuk mengingat hal hal penting dan dapat dituliskan tanpa terbaca di browser.


# Multimedia
untuk html kita dapat menambahkan foto video serta audio dalam vscode untuk dimasukkan di browser caranya ialah seperti berikut :
## menambah foto
untuk menambah foto pada teks editor vscode kita ==menggunakan tag `<img>`== dengan ==dibantu atribut "*src*"== lalu masukkan lah link foto yang ingin dimasukkan. lalu untuk mengatur *tinggi* dan *lebar* dengan ==atribut tinggi : "*height*" dan lebar : "*weight*"==.
Kode Program :
![Gambar 11](Aset/IMG5/IMG5_(4).jpg)
Hasil Program :
![Gambar 12](Aset/IMG5/IMG5_(5).jpg)

## menambah video
untuk menambah video dalam teks editor *vscode* kita menggunakan tag `<video>` dengan bantuan atribut ==*src=" "*== dan di isi dengan nilai atribut yaitu *nama videonya* contoh nya ialah seperti berikut.

**membuat aset untuk video :**
![Gambar 13](Aset/IMG5/IMG5_(6).jpg)

**Kode Program :**
![Gambar 14](Aset/IMG5/IMG5_(7).jpg)

**Hasil Program :** 
![Gambar 15](Aset/IMG5/IMG5_(8).jpg)

**Penjelasan :**
jadi pertama kita buat folder untuk aset *video* (opsional) lalu kita ketikkan tag serta atribut dan nilai atribut yaitu `src="*tempat dan nama video*"` dan kita dapat menambahkan atribut seperti :
- controls : untuk memberi button pada video
- loop : untuk mengulang otomatis video ketika selesai 
- muted : untuk menon-aktifkan suara saat awal masuk
- autoplay : untuk memulai otomatis video saat awal masuk

## menambah audio
dan yang terakhir untuk menambahkan audio pada *vscode* kita dapat menggunakan tag `<audio>` dengan atribut ==*src*== dan di isi dengan nilai atribut (tempat dan nama dokumennya) langkah langkah nya ialah seperti berikut :

**kode program :**
![Gambar 16](Aset/IMG5/IMG5_(9).jpg)

**hasil program :**
![Gambar 17](Aset/IMG5/IMG5_(10).jpg)






##### Pertemuan 6
# Pengenalan Iframe
Iframe ialah saran untuk memasukkan tampilan atu layout sebuah website ke website buatan kita atau simpelnya ==website dalam website==. Dan untuk tag ialah `<iframe>` dan menggunakan atribut *src* dan di isi dengan **link dari website tujuan** contoh nya ialah seperti berikut :

**kode program** :
![Gambar 18](Aset/IMG6/IMG6_(1).jpg)

**hasil program :**
![Gambar 19](Aset/IMG6/IMG6_(2).jpg)

**penjelasan :** 
Simpelnya iframe berfungsi untuk menampilkan website lain dalam website kita da kita dapat mengatur ukuran tinggi serta lebarnya lalu ada beberapa website yang butuh akses untuk melakukan iframe dengan website nya.

# Pengenalan Table

Dalam **HTML** kita dapat membantu "table" dengan menggunakan tah `<table>` dengan dibantu dengan beberapa atribut.

## Contoh program 
```html
<table border="3">
    <tr>
        <th rowspan="2">Nama</th>
        <th colspan="2">Asal Institusi</th>
    </tr>
    <tr>
        <th>Sekolah</th>
        <th>Kampus</th>
    </tr>
    <tr>
        <td>Fachri Ramadhan</td>
        <td>MAN 2 Makassar</td>
        <td>Universitas Hasanuddin</td>
    </tr>
    <tr>
        <td>Hayril Abizali</td>
        <td rowspan="2">SMK 7 Makassar</td>
        <td align="center" rowspan="2">Kerja</td>
    </tr>
    <tr>
        <td>Rahmat Ramadhan</td>
    </tr>
    <tr>
        <td>Fachri Ramadhan</td>
        <td>MAN 1 Makassar</td>
        <td>Universitas Muhammadiyah</td>
   </table>
```

## Hasil program 
![Gambar 20](Aset/IMG6/IMG6_(3).jpg)


## **Tag `<table>`**
 tag table berfungsi sebagai pembuka untuk struktur tabel sehingga tabel dapat terbentuk dan tag ini tetap memerlukan bantuan dari beberapa elemen serta atribut.
 
## Elemen **`<tr>`, `<th>` & `<td>`**
- `<tr>`
 untuk elemen `<tr>` digunakan untuk menjadi wadah pengelompokan `<th>` ataupun `<td>`
- `<th>` 
 untuk elemen ini berfungsi sebagai tempat penulisan *field* pada table yang akan digunakan 
- `<td>`
 untuk elemen ini berfungsi sebagai tempat penulisan *record* pada table yang akan digunakan 
 
## Analisis program 
Pada table di atas telah di dibuat table dengan tag `<table>`lalu menggunakan elemen `<tr>` yang berfungsi untuk tempat penulisan setiap baris baru di tabel, setelah itu kita menuliskan tag `<th>` yang berfungsi untuk tempat menuliskan *field* atau judul tabel, dan di akhiri dengan tag `<td>` yang berfungsi sebagai wadah untuk menuliskan *record* atau isi dari tabel dan ditutup kembali dengan tag `</table>`.


> [!Info]- Fungsi Elemen
>> - rowspan : berfungsi untuk menyatukan dua baris 
>> - colspan : berfungsi untuk menyatukan dua kolom
>> - border : memiliki tingkat dan berfungsi untuk membuat     kerangka pada tabel
>> - align : terbagi menjadi 4 dan berfungsi untuk mengatur rata kiri kanan teks


> [! Faq]- Why??
>> Kenapa pada *record* Rahmat tidak di isi sekolah dan kampus?
>> : Alasannya karena pada *record* Hayril telah di isi dengan elemen "rowspan".
>> 






##### Pertemuan 7
# Form
## Penjelasan Form…
Elemen `<form>` HTML digunakan untuk mendefinisikan form yang digunakan untuk mengumpulkan inputan dari pengguna website. Tag ini digunakan untuk mengkoleksi inputan dari user, konsep ini sama seperti konsep formulir di dunia nyata.

Dengan kata lain tag `<form>` merepresentasikan sebuah "formulir" di mana satu formulir bisa memiliki banyak kolom isian.

Form HTML berisikan elemen-elemen form lainnya. Elemen `<form>` digunakan untuk menampung macam-macam elemen yang berkaitan dengan sebuah form, seperti text fields, checkbox, radio button, tombol submit, dan banyak lagi yang dapat diedit kemudian ditulis untuk dikirim pada sebuah server untuk selanjutnya diproses guna mendapatkan informasi tertentu dari atau untuk user.

Umumnya, sebuah website selalu memiliki fitur form, contoh paling umum yang sering kita temui adalah seperti form login, form sign up, form komentar di suatu blog/media.


## Input
Elemen `<input>` adalah elemen form yang paling penting. Elemen `<input>`dapat ditampilkan dalam beberapa cara, tergantung pada nilai atribut type yang digunakan. Berikut adalah beberapa contoh nilai dari atribut type:

1. text digunakan untuk mengambil isian berupa teks. Contohnya seperti nama. contohnya ialah seperti berikut :
 ```html
<b>Nama:</b><br>
<input type="text"><br><br>
```
   Hasil Program :
   ![Gambar 18](Aset/IMG7/IMG7_(1).jpg)

2. password digunakan untuk mengambil isian berupa kata sandi atau sesuatu yang bersifat rahasia. Tipe ini akan mengubah semua karakter yang diketikkan ke dalam karakter bulat. Contoh ialah seperti berikut :
 ```html
<label> Password Anda : </label>
<input type="password>">
```
   Hasil Program :
   ![Gambar 22](Aset/IMG7/IMG7_(2).jpg)

3. radio digunakan sebagai kolom isian bertipe pilihan yang menawarkan beberapa opsi kepada user namun tetapi hanya satu opsi saja yang boleh dipilih. Contohnya seperti jenis kelamin atau agama. Contohnya ialah seperti berikut :
```html
<b>Jenis Pembyaran:</b><br>
<input type="radio" name="JP">
<label>Tunai</label>

<input type="radio" name="JP">
<label>Transfer</label><br><br>  
```
    
   Hasil Program :
   ![Gambar 24](Aset/IMG7/IMG7_(3).jpg)
    

Perlu diperhatikan bahwa untuk penggunaan tipe radio yang berkategori set pilihan yang sama mengharuskan nilai name -nya juga sama.

Opsi default dapat dilakukan dengan menambahkan atribut checked pada elemen opsi yang dijadikan sebagai opsi default.

4. checkbox digunakan untuk memberikan daftar pilihan dalam satu set opsi. User dapat memilih satu atau bahkan lebih dari satu pilihan pada tipe ini. Hal ini berbeda dengan tipe sebelumnya yaitu radio yang hanya memungkinkan user untuk memilih satu pilhan saja. Contoh penggunaan checkbox seperti daftar makanan kesukaan, daftar olahraga yang tidak disukai, dan yang semisalnya.
Elemen `<form>` HTML digunakan untuk mendefinisikan form yang digunakan untuk mengumpulkan inputan dari pengguna website. Tag ini digunakan untuk mengkoleksi inputan dari user, konsep ini sama seperti konsep formulir di dunia nyata. Contohnya ialah seperti berikut :
```html
<b>Waktu Pengiriman:</b><br>
    <input type="checkbox">
    <label>Pagi</label>

    <input type="checkbox">
    <label>Siang</label>

    <input type="checkbox">
    <label>Sore</label>

    <input type="checkbox">
    <label>Malam</label><br><br>
```
  Hasil Program :
  ![Gambar 25](Aset/IMG7/IMG7_(4).jpg)
  

## Label
- Elemen label memiliki fungsi khusus untuk melabeli sebuah kolom inputan. Ketika screen reader membaca konten halaman HTML, lalu menemukan sebuah inputan, ia akan membaca label yang bersangkutan.
- Fungsi lain dari tag `<label>` adalah ketika kita mengklik label, maka browser akan meletakkan fokus pada kolom isian yang terhubung dengannya. Syarat yang perlu diperhatikan yaitu dengan menghubungkan sebuah `<label>`dan `<input>` dengan atribut `<for>` untuk `<label>`, dan atribut `<id>` pada  dengan nilai untuk kedua atribut tersebut mesti sama persis.

## Select
- Elemen `<select>` berguna dalam mendefinisikan sebuah tombol ==dropdown== yang dimana user dapat memilih salah satu dari banyak pilihan. 
- `<aside>`Elemen `<select>` nantinya berperan sebagai kontainer atau pembungkus dari elemen `<option>` yang berperan sebagai daftar pilihan atau opsi.`</aside>`
- Elemen `<select>` hampir mirip fungsinya dengan `<input type=”radio">` akan tetapi baiknya elemen `<select>` digunakan untuk memilih satu pilihan yang terdapat banyak opsi di dalamnya, sedangkan `<input type=”radio">` lebih baiknya untuk digunakan jika  user diarahkan memilih hanya satu pilihan yang opsi pilihannya tidak terlalu banyak. Contoh penggunaan elemen ini seperti memasukkan pilihan berupa asal daerah atau yang semisalnya.Penting untuk diketahui  bahwasanya opsi yang aktif secara default adalah adalah opsi yang pertama. Akan tetapi, kita bisa mengatur opsi mana yang aktif secara default dengan menambahkan atribut selected pada suatu `<option>` yang ingin dijadikan sebagai opsi default. Contohnya ialah seperti berikut :
  ![Gambar 26](Aset/IMG7/IMG7_(5).jpg)

## **Text Area**
- Elemen `<textarea>` berguna untuk mengambil inputan user berupa teks yang dapat memuat *lebih dari satu baris*. Jika dibandingkan dengan elemen `<input>` teks biasa, elemen `<textarea>` memiliki ukuran tinggi yang lebih besar. Element textarea bisa diisi lebih dari satu baris dengan menekan enter. Atribut yang dapat digunakan untuk mengatur kuran dari textarea yaitu rows untuk jumlah baris, sedangkan atribut cols untuk lebarnya.
![Gambar 27](Aset/IMG7/IMG7_(6).png)

## **Button**
- Elemen `<button>` yang berada di dalam sebuah form akan otomatis dianggap sama fungsinya seperti `<input type="submit">`. Jika ingin membuat tombol biasa yang tidak men-submit `<form>` dapat dilakukan dengan menambahkan atribut type="button".
- Beberapa atribut yang digunakan pada contoh di atas yang perlu untuk diperjelas yaitu sebagai berikut:

```html

 <input type="submit" value="kirim">

  <input type="reset" value="reset">

```
dan hasilnya akan seperti dibawah ini :
![Gambar 28](Aset/IMG7/IMG7_(7).png)






