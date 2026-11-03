# Misi Pencernaan — Website Pembelajaran SMP

Website statis untuk mempelajari perjalanan makanan pada sistem pencernaan manusia. Tidak membutuhkan database, backend, login, framework, atau instalasi dependency.

## Isi folder

- `index.html` — website interaktif (HTML, CSS, dan JavaScript dalam satu file).
- `materi-sistem-pencernaan.docx` — dokumen materi yang disertakan, tersedia untuk diunduh dari website.

## Fitur

- Tampilan responsif untuk HP dan desktop.
- 7 checkpoint: mulut, kerongkongan/esofagus, lambung, usus halus, usus besar, rektum, dan anus.
- Penjelasan setingkat SMP, diagram organ yang menyorot bagian yang sedang dipelajari, dan catatan pengamatan miniatur.
- Narasi suara menggunakan fitur text-to-speech browser (jika didukung perangkat/browser).
- 1 pertanyaan pilihan ganda pada setiap checkpoint, umpan balik, dan skor akhir.
- Informasi organ pendukung: hati, kantung empedu, dan pankreas.
- Tombol untuk mengunduh dokumen materi.

## Cara publish ke GitHub Pages

1. Buat repository GitHub baru, misalnya `misi-pencernaan`.
2. Unggah `index.html` dan `materi-sistem-pencernaan.docx` ke **root** repository (bukan di dalam subfolder).
3. Buka **Settings → Pages** pada repository.
4. Pada bagian **Build and deployment**, pilih **Deploy from a branch**.
5. Pilih branch `main` dan folder `/(root)`, lalu tekan **Save**.
6. Tunggu proses deployment selesai. URL umumnya berbentuk `https://USERNAME.github.io/NAMA-REPOSITORY/`.
7. Buka URL tersebut dari HP untuk menguji tombol, audio, kuis, serta unduhan dokumen. Setelah itu, buat QR Code yang mengarah ke URL final tersebut.

> Catatan: URL GitHub Pages di atas hanya contoh pola alamat. Gunakan URL persis yang ditampilkan GitHub pada bagian Pages setelah deployment.

## Menjalankan secara lokal

Cukup buka `index.html` dengan browser. Agar perilaku unduhan dokumen konsisten, biarkan file DOCX berada satu folder dengan `index.html`.

## Sumber materi

Materi inti organ mengikuti dokumen yang disertakan. Penjelasan proses pencernaan dan organ pendukung diperkaya menggunakan OpenStax, *Anatomy & Physiology*, bagian [Digestive System Processes and Regulation](https://openstax.org/books/anatomy-and-physiology/pages/23-2-digestive-system-processes-and-regulation).
