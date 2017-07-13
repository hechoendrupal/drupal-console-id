# drupal-console-id
DrupalConsole Indonesian Language / Bahasa Indonesia

# Versi Bahasa Indonesia

## Pemakaian

Proyek Drupal Console diinstal pada tiap website Drupal 8 dengan menggunakan bahasa Inggris sebagai bawaan.

Untuk menginstal Paket Drupal Console dengan bahasa Indonesia jalankan perintah berikut ini

```
$ composer require drupal/console-id
```

### Instal Drupal Console

Untuk menginstal versi yang sesuai dari proyek Drupal Console untuk instalasi drupal anda, jalankan perintah composer berikut ini

```
$ composer require drupal/console:~1.0 --prefer-dist --optimize-autoloader
```

### Instal Drupal Console launcher

Untuk mengindari konflik antara rilis Drupal dan versi Drupal Console di antara rilis major dan minor Drupal, dibuatlah Drupal Console launcher untuk memuat perintah-perintah Drupal Console yang tersedia untuk setiap website Drupal 8.

Ikuti perintah di bawah ini untuk menginstal aplikasi global untuk Drupal Console launcher.

```
$ curl https://drupalconsole.com/installer -L -o drupal.phar
# Atau
$ php -r "readfile('https://drupalconsole.com/installer');" > drupal.phar

$mv drupal.phar /usr/local/bin/drupal
$ chmod +x /usr/local/bin/drupal
```

### Kontribusi

Jika anda ingin berkontribusi pada penerjemahan ini, anda perlu mengikuti langkah-langkah ini

- Fork repository ini menggunakan link berikut [https://github.com/hechoendrupal/drupal-console-id#fork-destination-box](https://github.com/hechoendrupal/drupal-console-id#fork-destination-box)
- Clone repository anda yang telah di-fork di mesin lokal anda.
- Set up upstream

Supaya terbarukan dengan kontribusi lainnya anda harus menyetel koneksi dengan repository utama menggunakan perintah git berikut ini

```
$ git remote add upstream git@github.com:hechoendrupal/drupal-console-id.git
```

Untuk mengambil kontribusi terakhir sebelum memulai, anda harus menjalankan perintah-perintah berikut ini
```
$ git fetch upstream
$ git merge upstream/master
```

Catatan: Push perubahan pada repository yang telah anda fork untuk membuat PR per hari supaya mencegah terjadinya konflik dengan kontributor-kontributor lainnya.

# English Version

Check instructions at [https://github.com/hechoendrupal/drupal-console-en](https://github.com/hechoendrupal/drupal-console-en)
