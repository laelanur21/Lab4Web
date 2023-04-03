## Praktikum 4: PHP Modular

Nama: Laela Nur Rohmah

Nim: 312110425

Kelas: TI.21.A.3

## 1. Membuat file baru dengan nama header.php

![img 1](img/lab4_mod_header.jpg)

## 2. Membuat file baru dengan nama footer.php

![img 2](img/lab4_mod_footer.jpg)

## 3. Membuat file baru dengan nama home.php

![img 3](img/lab4_mod_home.jpg)

## 4. Membuat file baru dengan nama about.php

![img 4](img/lab4_mod_about.jpg)

## MEMBUAT ROUTING

menyiapkan file utama (index.php) yang berisi routing untuk mengakses banyak 
halaman. 

cara aksesnya :

• Halaman Home ( http://localhost/lab4_php_modular/index.php?mod=home )

• Halaman About ( http://localhost/lab4_php_modular/index.php?mod=about )

## 5. Membuat file baru dengan nama index.php

![img 5](img/lab4_mod_index.jpg)

Dengan hasil Output seperti:

•home:

![img 6](img/lab4_mod_home_output.jpg)

•about:

![img 7](img/lab4_mod_about_output.jpg)

## Aktivasi mod_rewrite (.htaccess)

Langkah awal yang harus disiapkan adalah aktivasi mod_rewrite pada webserver Apache2 pada configurasi httpd.conf.
![img 8](img/Apache_config.png)

![img 8](img/aktivasi_mod_rewrite.jpg)

Aktifkan LoadModule mod_rewrite dengan cara melakukan un-comment pada baris tersebut.

## 7. Membuat file baru dengan nama .htaccess

![img 9](img/lab4_mod_htaccess.jpg)

Cara aksesnya menjadi:

• Halaman Home ( http://localhost/lab4_php_modular/home )

• Halaman About ( http://localhost/lab4_php_modular/about )

Dan Hasil Outputnya yaitu:

•home:

![img 10](img/lab4_mod_home_output_baru.jpg)

•about:

![img 11](img/lab4_mod_about_output_baru.jpg)

## TUGAS 4

Mengimplementasikan konsep modularisasi pada kode program praktikum 3 tentang database, sehingga setiap halamannya memiliki template tampilan yang sama

## 1. tampilan .htaccsess

![img 12](img/lab4_tugas_htaccess.jpg)

## Tampilan output

## 2. Tampilan home.php:

![img 13](img/lab4_tugas_home_output.jpg)

## 3. Tampilan about.php:

![img 14](img/lab4_tugas_about_output.jpg)

## 4. Tampilan contact.php:

![img 15](img/lab4_tugas_contact_output.jpg)

## 5. Tampilan tambah.php:

![img 16](img/lab4_tugas_tambah_output.jpg)

## 6. Tampilan ubah.php:

![img 17](img/lab4_tugas_ubah_output.jpg)