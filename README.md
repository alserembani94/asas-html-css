# Asas HTML dan CSS

Selamat datang ke bahagian pertama Online Coding Bootcamp oleh KelasProgramming.

Repositori ini bertujuan untuk berkongsi kod dalam pengajaran sesi kelas bahagian pertama.

Untuk mendapatkan semua kod dalam repositori ini, anda hanya perlu klonkan projek ini ke dalam komputer masing-masing. Anda boleh rujuk pada [langkah klon projek](#langkah-klon-projek)

---

## Prasyarat

Sebelum anda mengklonkan projek ini, pastikan anda sudah memasang Git ke dalam komputer anda. Untuk tujuan tersebut, bergantung kepada sistem operasi (*operating system, OS*) yang digunakan oleh komputer anda.

### Windows

Anda mempunyai dua pilihan:

#### 1. Memasang Laragon - https://laragon.org/download/
Anda boleh memasang Laragon ke dalam komputer anda dan gunakan peralatan sedia ada. Untuk memastikan Git tersedia bersama Laragon, sila buka `terminal` dalam Laragon, dan taip `git --version`.

ATAU

#### 2. Memasang Git - https://git-scm.com/download/win
Anda boleh memasang Git terus ke dalam komputer anda. Untuk tujuan menggunakan git, saya sarankan untuk menggunakan `Powershell` dan tidak menggunakan `cmd`.

Ketika membuat pemasangan, sila pastikan anda memilih VSCode sebagai IDE pilihan anda. Memasang Chocolatey adalah pilihan anda, tetapi saya rekemen anda untuk memasangnya untuk tujuan akan datang.

Untuk memastikan Git tersedia, sila buka Powershell dan taip `git --version`.

### MacOS

Git sudah tersedia sebagai satu peralatan mesti dalam sistem operasi MacOS. Untuk menggunakannya, anda hanya perlu menggunakan `terminal` untuk menggunakan peralatan Git. Untuk memastikan Git tersedia, buka terminal dan taip `git --version`.

### Linux

Git sudah tersedia sebagai satu peralatan mesti dalam kebanyakan sistem operasi Linux (bergantung kepada distro yang dipakai). Untuk menyemak pemasangan Git, buka terminal dan taip `git --version`.

### Langkah semakan pemasangan git

Untuk memastikan pemasangan Git berjaya, anda hanya perlu buka terminal (untuk Laragon, Linux dan MacOS) atau Powershell (untuk Windows), dan taip `git --version`. Sekiranya output yang dihasilkan seperti yang di bawah:

```bash
git version X.XX.X
```

Anda sudah berjaya memasang git ke dalam sistem anda!

Anda juga boleh merujuk [How to Install Git](https://www.atlassian.com/git/tutorials/install-git) oleh Atlassian.

---

## Langkah Klon Projek

Untuk klon projek ke komputer anda, anda perlu menggunakan peralatan Git.

Dalam terminal (MacOS, Linux dan Laragon) atau Powershell (Windows) anda, sila taip arahan berikut:

```bash
git clone https://github.com/alserembani94/asas-html-css.git
```

> Pautan ini juga boleh didapati di butang hijau di atas sebelah kanan halaman ini.

> Sila pastikan anda tahu kedudukan direktori anda sekarang. Anda boleh menggunakan arahan komputer mengikut sistem operasi masing-masing. Ini penting, supaya anda tahu kedudukan fail yang anda akan klon selepas proses ini.

Setelah berjaya, anda boleh memasuki direktori yang telah diklon sebentar tadi dan buka di VSCode.

```bash
code ./asas-html-css
```

---

## Inkuiri

Sekiranya terdapat kesukaran dalam klon projek ini, sila maklumkan kepada tenaga pengajar atau mentor anda. Anda juga boleh bertanyakan dalam kumpulan komuniti dalam WhatsApp.

---

## Tambahan

Sekiranya anda mendapati ralat ketika anda mengklon projek seperti di bawah:

```
Make sure you configure your 'user.email' and 'user.name' in git
```

Sila ikut arahan berikut:
```
git config --global user.name "<NAMA_ANDA>"
git config --global user.email "<EMEL_GITHUB_ANDA>"
```

Sila gantikan `<NAMA_ANDA>` dan `<EMEL_GITHUB_ANDA>` kepada nama dan email anda.

Di bawah hanya sekadar contoh:
```
git config --global user.name "Kluangman"
git config --global user.email "kluangman@gmail.com"
```

Setelah berjaya, anda boleh teruskan urusan klon projek.