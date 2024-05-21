# ANATOMI css
Anatomi css terdiri dari Selector, Property dan Property Value untuk contoh lebih jelasnya kita akan masuk kedalam contoh dibawah dimana akan dijelaskan contoh dari ketiga anatomi css.

```css
P{
 Color: red ;
}
```

## DIV&SPAN

DIV adalah elemen tingkat blok yang digunakan untuk membuat bagian, sedangkan SPAN adalah elemen sebaris untuk menata teks atau elemen sebaris lainnya

### DIV
Div ialah tag yang digunakan untuk mengetikkan sesuatu namun cakupan areanya akan
mengambil satu block/baris.
### span

Span ialah tag yang digunakan untuk mengetikkan sesuatu namun cakupan areanya akan mengambil sesuai yang diketikkan saja.

# percobaan 1

```css
<style>
   P {
   Color:red;
   }
   </style>
   <p>welcom css </p>
```

penjelasan:
disini isi dari tag p berubah menjadi berwarnah merah di akibatkan oleh style css tepatnya property color yang dibarengi dengan value red sehinggan hasil dari tag p yang telah dipanggil oleh style css berubah menjadi warna merah.

# percobaan 2
Kode css:
```css
<style>
      p {
        color:red;
      }
      button {
          width:150px;
          height:50px;

          border:none;
       font-size:20px;
     background-color:yellow;
      }
    </style>
```

# border
garis batas yang bisa digunakan di setiap elemen. Untuk memperlihatkan garis batas dari sebuah elemen, gunakan properti border pada CSS.

## BEFORE
![[IMG-20240429-WA0002.jpg]]


## After
![[IMG-20240429-WA0004.jpg]]

# font size
Font Size, merupakan atribut yang digunakan dalam Tag Font, untuk mengatur ukuran huruf. Font Face, atribut ini digunakan untuk mengtur jenis huruf yang akan digunakan.

## BEFORE 

![[IMG-20240429-WA0005.jpg]]
## AFTER 
![[IMG-20240429-WA0004 1.jpg]]

# background-color
merupakan attribute untuk menentukan warna pada halaman HTML
## BEFORE 
![[IMG-20240429-WA0007.jpg]]
## AFTER
![[IMG-20240429-WA0004 1 1.jpg]]

# pemanggilan css
untuk pemanggilan css dibagi menjadi tiga bagian/cara dan ketiga cara tersebut akan dijelaskan di materi di bawah, untuk lebih jelasnya kita akan langsung masuk ke materi dari tiga cara pemanggilan tersebut.

## Inline
Untuk Inline pemanggilannya ialah langsung bersamaan dengan tag yang ingin diketikkan misalnya seperti kode program berikut :
```html
<p style=color: red;>ini cara pemanggilan css inline</p>
```
## internal
Lalu untuk internal cara pemanggilannya ialah dengan diketikkan di dalam dokumen html yang telah kita buat namun berbeda dengan Inline, contoh nya ialah seperti kode program dibawah berikut :

```html 
<head>
	<style>
		p {
		 color: red;
		}
	</style>
</head>
<body>
	<p>ini adalah pemanggilan css internal </p>
</body>
```
# External 
Sedangkan External cara pemanggilan ini ialah dengan membuat dokumen khusus css lalu menghubungkan antara dokumen html dan css dengan tag <link> untuk contoh programnya akan seperti berikut :
```html 
<head>
	<link rel="stylesheet" href="nama_dokumen_css.css"
</head>
```
# Selector
Untuk selector css dibagi menjadi 3 cara yaitu Elemen Selector, Class selector dan Id selector
untuk penjelasan kebih lanjutnya akan kita bahas di materi di bawah ini.
## Elemen selector
Untuk Elemen selector kita melakukan pemanggilan di dalam dokumen html dengan menyebutkan nama tag nya misalnya ialah seperti di bawah ini :
```html 
<style>
	div {
	 color: red;
	}
</style>
```
