<p align="center">
    <a href="https://github.com/sandinur157" target="_blank"><img src="https://media.tenor.com/GfSX-u7VGM4AAAAC/coding.gif" width="400"></a>
</p>

## Tentang Aplikasi

Aplikasi <b>Absensi menggunakan livewirw</b>  yang digunakan untuk melakukan absensi dan melihat laporan absensi karyawan. Enjoy to use my apps👋🏻👋🏻.

## Instalasi
#### Via Git
```bash
git clone https://github.com/Kantrawibawa10/Laravel-Livewire-Absensi.git
```

### Download ZIP
[Link](https://github.com/Kantrawibawa10/Laravel-Livewire-Absensi/archive/refs/heads/master.zip)


# **Absensi App**

Features

-   CRUD Positions (CRUD Jabatan/Posisi)
-   CRUD Users (Admin, Operator and Users (Employees))
-   CRUD Holidays (CRUD Hari Libur)
-   CRUD Attendances (Can have multiple attendances and can using only button or presence using QRCode)
-   Using Datatables (Powergrid livewire)
-   Can Export to Excel and CSV
-   and more...

## Cara Install di Local

-   Hal yang harus dipersiapkan
    -   git
    -   composer
    -   php v8.1

```sh

# install semua package
composer install

# pilih salah satu
# 1. windows
copy .env.example .env
# 2. unix (ubuntu, mac os and others)
cp .env.example .env

# setelah itu, setting .env file seperti nama database (DB_DATABASE), username dan passwordnya
# lalu buat database baru dari phpmyadmin atau cli langsung juga bisa dengan nama sesuai DB_DATABASE yang ada di file .env
php artisan key:generate
php artisan migrate
php artisan db:seed
php artisan serve

# lalu buka browser dengan url: http://localhost:8000/
```

## How to install/use (english)


-   Install all packages

```sh
composer install
```

-   Copy/rename file .env.example to .env

```sh
# windows
copy .env.example .env
# unix (ubuntu, mac os and others)
cp .env.example .env
```

-   Configure .env file
    <br>
    Open your .env file and change the database name (DB_DATABASE) to whatever you have, username (DB_USERNAME) and password (DB_PASSWORD) field correspond to your configuration.

-   Create database
    <br>
    Create a database according to the name in DB_DATABASE in the .env file

-   Run artisan commands

```sh
php artisan key:generate
php artisan migrate
php artisan db:seed
php artisan serve
```

-   And go to http://localhost:8000/
