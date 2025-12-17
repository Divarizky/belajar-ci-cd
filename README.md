# belajar-ci-cd

Belajar Continuous Integration (CI) menggunakan GitHub Actions.

## Deskripsi
Projek ini digunakan untuk belajar dan mempraktikkan konsep dasar Continuous Integration (CI) dengan menggunakan GitHub Actions sebagai platform untuk menjalankan pipeline CI.

## Fitur
- Pipeline CI sederhana menggunakan GitHub Actions
- Workflow yang berjalan pada saat push dan pull request ke branch main
- Contoh job yang menampilkan pesan "Hello World"
- Job untuk menampilkan informasi sistem

## Struktur Projek
- `.github/workflows/ci.yml` - Konfigurasi GitHub Actions untuk pipeline CI
- `README.md` - Dokumentasi projek

## Workflow
Workflow dalam file `ci.yml` memiliki dua jobs:
1. `hello-job` - Menampilkan pesan "Hello World (Github Actions)"
2. `info-job` - Menampilkan informasi sistem seperti username dan OS info

## Trigger
Pipeline akan dijalankan ketika:
- Ada push ke branch `main`
- Dibuka pull request ke branch `main`