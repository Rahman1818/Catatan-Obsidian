Anggota:
1.ABD. Rahman N.
2.muh.zafran rizki

# pengertian
`z-index` adalah properti CSS yang menentukan tumpukan relatif dari elemen dalam tata letak (layout) sebuah halaman web. Ini mengontrol bagaimana elemen ditempatkan di atas atau di bawah elemen lain. Semakin tinggi nilai `z-index`, semakin tinggi elemen tersebut akan ditumpuk di atas elemen lainnya.

Misalnya, jika Anda memiliki dua elemen tumpang tindih, yang satu memiliki `z-index: 1` dan yang lain memiliki `z-index: 2`, maka elemen dengan `z-index: 2` akan muncul di atas elemen dengan `z-index: 1`

Namun, nilai `z-index` hanya berlaku untuk elemen yang memiliki posisi terdefinisi, seperti posisi `absolute`, `relative`, atau `fixed`.

Contoh program:
```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Z-Index Example</title>
<link rel="stylesheet" href="Z-Index.css">
</head>
<body>
  <div class="container">
    <div class="box box1">Box 1</div>
    <div class="box box2">Box 2</div>
    <div class="box box3">Box 3</div>
  </div>
</body>
</html>

```

```css
.container {
  position: relative;
  height: 200px;
}

.box {
  position: absolute;
  width: 100px;
  height: 100px;
  background-color: #3498db;
  color: white;
  text-align: center;
  line-height: 100px;
  box-shadow: 0 4px 6px;
}

.box1 {
  top: 20px;
  left: 20px;
  z-index: 3; /* Box 1 di atas */
}

.box2 {
  top: 50px;
  left: 50px;
  z-index: 2; /* Box 2 di tengah */
}

.box3 {
  top: 80px;
  left: 80px;
  z-index: 1; /* Box 3 di bawah */
}
```

Penjelasan:
- Kode HTML memiliki tiga elemen `div` dengan kelas `.box`, yang mewakili tiga kotak.
- Setiap kotak memiliki properti `position: absolute;` untuk menetapkan posisinya relatif terhadap elemen induknya.
-  Properti `z-index` digunakan untuk mengatur tumpukan (stacking) elemen. Semakin tinggi nilai `z-index`, semakin tinggi elemen tersebut dalam tumpukan.
- Dalam contoh ini, kotak pertama (`box1`) memiliki `z-index: 3;`, kotak kedua (`box2`) memiliki `z-index: 2;`, dan kotak ketiga (`box3`) memiliki `z-index: 1;`. Oleh karena itu, kotak pertama akan berada di atas kotak kedua dan ketiga.

Hasil program:

![[Screenshot_20240418-140559_Acode.jpg]]

**Kegunaan z-index pada web** :

Properti `z-index` pada web sangat penting untuk mengatur tumpukan (stacking) elemen-elemen HTML. Hal ini memungkinkan pengembang web untuk mengontrol urutan tampilan elemen-elemen, menentukan elemen mana yang akan muncul di depan atau di belakang elemen-elemen lainnya. Beberapa kegunaannya meliputi:

1.**Mengatasi Tumpang Tindih (Overlap)**: Saat ada elemen-elemen yang tumpang tindih di halaman web, properti `z-index` memungkinkan pengembang untuk menentukan elemen mana yang harus ditampilkan di depan dan elemen mana yang harus ditampilkan di belakang.
2.**Animasi dan Efek Visual**: Dalam pengembangan animasi dan efek visual, penggunaan `z-index` dapat menciptakan efek tumpukan yang menarik, seperti animasi kartu atau overlay gambar.
3.**Pop-up dan modals**: Menyajikan pop-up atau modals yang muncul di atas konten utama dengan menggunakan `z-index`, sehingga fokus pengguna tetap pada pesan atau tindakan yang ditampilkan.
4.**Slider atau carousel**: Mengatur tumpukan slide dalam slider atau carousel, sehingga pengguna dapat melihat slide saat ini di depan, dan slide lainnya di belakang.
5.**Tooltip**: Memastikan tooltip muncul di depan konten utama, sehingga informasi tambahan mudah dilihat oleh pengguna.

**KESIMPULAN :
Secara keseluruhan, `z-index` pada web memungkinkan pengontrolan tumpukan elemen, memungkinkan penempatan elemen-elemen di depan atau di belakang yang lain. Ini sangat penting untuk membuat tampilan yang terorganisir dan interaktif, seperti menyajikan menu navigasi yang terapung, menampilkan pop-up atau modals, mengatur slider, atau menampilkan tooltip dengan jelas kepada pengguna. Dengan menggunakan `z-index`, pengembang web memiliki fleksibilitas lebih dalam merancang tampilan yang efektif dan menarik.

