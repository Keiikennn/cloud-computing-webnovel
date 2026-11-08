# Pengembangan Aplikasi Pembaca Komik dan Web Novel Berbasis Cloud

## Informasi Proyek

- Mata Kuliah: Cloud Computing (PTI2802)
- Nama: Moch Fajri Aulia Nugraha
- NIM: 25832073012
- Kelas: 2B PTI
- Semester: Ganjil 2026/2027

## Deskripsi Proyek

Proyek ini bertujuan mengembangkan aplikasi pembaca komik dan web novel berbasis cloud yang memungkinkan pengguna mengelola koleksi bacaan serta menyimpan progres membaca.

## Problem Statement

Pengguna yang membaca komik dan web novel membutuhkan aplikasi yang dapat mengelola koleksi bacaan serta menyimpan progres membaca agar mereka dapat melanjutkan bacaan dari bagian terakhir yang telah dibuka.

## Target Pengguna

1. Pengguna yang membaca komik digital.
2. Pengguna yang membaca web novel.
3. Pengguna yang membutuhkan pengelolaan koleksi dan progres bacaan.

## Fitur Utama

1. Membaca komik digital.
2. Membaca web novel.
3. Mengelola koleksi bacaan.
4. Menyimpan progres membaca.
5. Melanjutkan bacaan dari progres terakhir.
6. Mencari koleksi bacaan.

## Arsitektur

Arsitektur deployment awal:

Internet → UFW → Caddy → Gunicorn → Flask

## Teknologi

- Ubuntu Server 24.04 LTS
- Python 3.12
- Flask
- Gunicorn
- systemd
- Caddy
- UFW
- Git
- GitHub

## Deployment

Status deployment: Belum dilakukan.

Public endpoint: Akan ditambahkan setelah deployment VPS.

Health check: `/health`

## Keamanan

- Menggunakan akun VPS non-root.
- Menggunakan autentikasi SSH berbasis key.
- Menggunakan UFW sebagai firewall.
- Backend hanya menerima koneksi melalui loopback.
- Tidak menyimpan secret di repository.

## Keterbatasan M03

- Belum menggunakan database produksi.
- Belum menggunakan Docker.
- Belum menggunakan CI/CD.
- Deployment awal menggunakan HTTP.
- Aplikasi berjalan pada satu VPS.

## Roadmap

- M03: Project inception dan first deployment.
- M04: DNS dan HTTPS.
- M05: Persistent data.
- M06: Containerization.
- M07: Infrastructure as Code.
- M09: CI/CD.
- M16: Final release.
