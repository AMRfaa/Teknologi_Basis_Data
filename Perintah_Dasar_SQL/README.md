# Perintah Dasar SQL
## 1. Pembuatan Basis Data
> ### a) Membuat basis data
```bash
>>> create database (nama database);
```
> ### b) Menghapus basis data 
```bash
>>> drop database (nama database);
```
> ### c) Melihat basis data yang ada
```bash
>>> show databases;
```

## 2. Pembuatan Tabel Dalam Basis Data
> ### a) Masuk ke dalam basis data
```bash
>>> use (nama database);
```
> ### b) Membuat tabel
```bash
>>> create table (nama database) (atribut kolom);
```
> ### c) Melihat tabel yang ada
```bash
>>> show tables;
```

## 3. Menghapus Tabel
```bash
>>> drop table (nama tabel);
```

## 4. Mengupdate atribut tabel
> ### a) Melihat deskripsi tabel
```bash
>>> desc (nama tabel);
```
> ### b) Menambah atribut
```bash
>>> alter table (nama tabel) add (nama atribut) (tipe data); 
```
> ### c) Memodifikasi atribut
```bash
>>> alter table (nama tabel) modify (nama atribut) (tipe data);
```
> ### d) Menghapus atribut
```bash
>>> alter table (nama tabel) drop column (nama kolom);
```

## 5. Mengisi tabel
> ### a) Mengisi tabel
```bash
>>> Insert into (Nama Tabel) (nama) velues (‘Anisa Muziya Rafa'); 
```
> ### b) Melihat semua isi data tabel 
```bash
>>> Select * from (nama tabel);
```

## 6. Mengupdate isian tabel
```bash
>>> update (nama tabel) set kelas = ‘B’ where nim = 240306014; 
```
