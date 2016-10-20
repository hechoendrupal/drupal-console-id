# drupal-console-id
DrupalConsole Indonesian Language / Bahasa Indonesia

# Versi Bahasa Indonesia

## Pemakaian

Proyek Drupal Console diinstal pada tiap website Drupal 8 dengan menggunakan bahasa Inggris sebagai bawaan.

Untuk menginstall Paket Drupal Console dengan bahasa Indonesia jalankan perintah berikut ini

```
$ composer require drupal/console-id
```

### Instal Drupal Console

Untuk menginstal versi yang sesuai dari proyek Drupal Console untuk instalasi drupal anda, julankan perintah composer berikut ini

```
$ composer require drupal/console:~1.0 --prefer-dist --optimize-autoloader
```

### Instal Drupal Console launcher

Untuk mengindari konflik antara rilis Drupal dan versi Drupal Console di antara rilis major dan minor Drupal, dibuatlah Drupal Console launcer untuk memuat perintah-perintah Drupal Console yang tersedia untuk setiap website Drupal 8.

Ikuti perintah di bawah ini untuk menginstal aplikasi global untuk Drupal Console launcher.

```
$ curl https://drupalconsole.com/installer -L -o drupal.phar
# Or
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

Untuk mengambil kontribusi terakhit sebelum memulai, anda harus menjalankan perintah-perintah berikut ini
```
$ git fetch upstream
$ git merge upstream/master
```

N.B: Push perubahan pada repository yang telah anda fork untuk membuat PR per hari supaya mencegah terjadinya konflik dengan kontributor-kontributor lainnya.

# English Version

## Usage

Drupal Console project it's installed per each Drupal 8 website with English language by default.

To installe Drupal Console package for Indonesian language run the following instructions

```
$ composer require drupal/console-id
```

### Install Drupal Console

To install the appropriate version of Drupal Console project for your drupal installation, run the following composer command

```
$ composer require drupal/console:~1.0 --prefer-dist --optimize-autoloader
```

### Install Drupal Console launcher

In order to avoid conflicts between Drupal release and have a Drupal Console version between major and minor releases in Drupal,  a Drupal Console launcher was created. n order to facilitate to load the Drupal Console commands available to each
Drupal 8 website,

Following the instruction below you could install the global application for Drupal Console launcher.

```
$ curl https://drupalconsole.com/installer -L -o drupal.phar
# Or
$ php -r "readfile('https://drupalconsole.com/installer');" > drupal.phar

$mv drupal.phar /usr/local/bin/drupal
$ chmod +x /usr/local/bin/drupal
```

### Contribute

If you want to contribute to this translation, you need to follow this steps

- Fork this repository following this link [https://github.com/hechoendrupal/drupal-console-id#fork-destination-box](https://github.com/hechoendrupal/drupal-console-id#fork-destination-box)
- Clone your repostory forked in your local machine.
- Set up upstream

In order to be updated with other contribution you must to setup a connected with main repository using the following git command

```
$ git remote add upstream git@github.com:hechoendrupal/drupal-console-id.git
```

To fetch the latest contribution before to start, you must run the next commands
```
$ git fetch upstream
$ git merge upstream/master
```

N.B: Push your changes to your forked repository in order to create PR per day to avoid any conflicts with other contributors.
