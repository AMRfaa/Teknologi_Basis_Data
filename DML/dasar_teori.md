# DML
## 1. Definisi DDL dan DML
> ### Data Definition Language (DDL)
> bahasa atau perintah pada SQL yangg digunakan untuk mendefinisikan data seperti membuat, menghapus dan mengubah data.
```bash
Perintah-perintah yang ada pada komponen DDL antara lain:
1)	CREATE
    Digunakan untuk membuat, seperti membuat database, membuat tabel, membuat view dan membuat index.
2)	DROP 
    Perintah yang digunakan untuk menghapus data-data yang telah di simpan pada databases (menghapus wadahnya, bukan hanya isinya).
3)	ALTER
    Kegunaan dari perintah alter adalah untuk merubah atribut pada suatu tabel (mengubah bentuk wadahnya, bukan isinya).
4)	TRUNCATE
    Kegunaan dari perintah truncate untuk menghapus semua record dari tabel, termasuk semua space yang dialokasikan untuk semua record yang dihapus.
5)	RENAME 
    Kegunaan perintahini untuk mengganti nama objek atau tabel yang ada di basis data.
```

> ### Data Manipulation Language (DML)
> sebuah metode quary yang dapat digunakan apabila DDL telah terjadi, sehingga fungsi dari Quary DML ini untuk melakukan pemanipulasian database yang telah dibuat (ini lebih kepada isinya, manipulasi terhadap isinya)
```bash
Perintah-perintah yang ada pada komponen DML yaitu:
1)	INSERT
    Perintah insert berfungsi untuk menambah record/data pada suatu tabel.
2)	UPDATE
    Perintah update berfungsi untuk menambah record didalam suatu kolom pada tabel.
3)	DELETE 
    Perintah delete berfungsi untuk menghapus record didalam suatu kolom pada tabel.
4)	SELECT 
    Perintah select merupakan perintah yang digunakan untuk menampilkan kolom dan record yang dipilih.
```

## 2. Perbedaan DDL dan DML
> ### DDL (Data Definition Language) digunkana untuk mendefinisikan atau emngatur struktur database, seperti membuat atau menghapus tabel.
> ### DML (Data Manipulation Language) digunakan untuk mengolah atau memanipulasi data di dalam tabel, seperti menambah, menghapus, atau menampilkan data.

## 3. ERD (Entity Relationship Diagram)
> ### Entity Relationship Diagram (ERD) adalah diagram berbentuk notasi grafis yang berada dalam pembuatan database yang menghubungkan antara data satu dengan yang lain

> ### Di dalam ERD terdapat 3 elemen dasar, yaitu:
>> #### a.	Entitas
>>> Entitas adalah objek dalam suatu database. Entitas dapat berupa manusia, tempat, benda, atau kondisi mengenai data yang dibutuhkan. Simbol dari entitas berbentuk persegi panjang.

>> #### b.	Atribut
>>> Atribut adalah informasi yang terdapat dalam entitas. Sebuah entitas harus memiliki primary key sebagai ciri khas entitas dan atribut deskriptif. Atribut biasanya terletak dalam tabel entitas atau dapat juga terpisah dari tabel. Simbol dari atribut berbentuk elips.

>> #### c.	Relasi
>>> Relasi di dalam ERD merupakan hubungan antara dua atau lebih entitas. Simbol dari relasi berbentuk belah ketupat. Relasi yang dapat dimiliki oleh ERD ada beberapa macam, yaitu : 
>>> 1)	One to One
> Satu anggota entitas dapat berelasi dengan satu anggota entitas lain.
>>> 2)	One to Many
> Satu anggota entitas dapat berelasi dengan beberapa anggota entitas lain
>>> 3)	Many to Many
> Beberapa anggota entitas dapat berelasi dengan beberapa anggota entitas lain
