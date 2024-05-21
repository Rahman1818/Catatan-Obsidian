## **ALTER**
![[Screenshot_20240423-133930_Termux.jpg]]
![[Screenshot_20240423-133930_Termux.jpg]]

# **MENAMBAHKAN KOLOM**
 ## **Struktur QUERY**
```MYSQL

Alter table nama_tabel add nama_kolom varchar(10) after nama_kolom
```

## **CONTOH Query**

```mysql
Alter table mobil add batas_peminjaman varchar(10) after peminjam
```

## **HASIL**
![[Screenshot_20240423-134331_Termux.jpg]]
## **PENJELASAN**
AFTER: opsional untuk digunakan, jika tidak menggunakan klausa ini maka secara default
kolom yang dibuat akan berada di akhir. Jika kolom ingin ditaruh pada awal kolom maka
gunakan klausa FIRST. *Silahkan tampilkan struktur tabel dan masukkan data ke kolom batas_peminjaman.
