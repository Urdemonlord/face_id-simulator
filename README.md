# Simulator Face ID

Proyek ini mensimulasikan sistem registrasi dan login wajah menggunakan webcam. Ini adalah demonstrasi sederhana dan tidak menyertakan teknologi pengenalan wajah yang sebenarnya.

## Fitur

- **Registrasi:** Tangkap foto menggunakan webcam Anda dan kaitkan dengan nama pengguna.
- **Login:** Tangkap foto dan simulasikan pencocokan wajah untuk "masuk" sebagai pengguna terdaftar.
- **Penyimpanan Lokal:** Data pengguna disimpan di localStorage browser.
- **Pergantian Tab:** Beralih dengan mudah antara tampilan registrasi dan login.

## Cara Menjalankan

1. **Unduh atau klon repositori ini.**
2. **Buka `index.html` di browser web Anda.**
3. **Izinkan akses webcam saat diminta.**

## Cara Kerja

- **Registrasi:**
    - Masukkan nama pengguna.
    - Klik "Capture Photo for Registration" untuk mengambil gambar.
    - Gambar yang diambil diubah menjadi data base64 dan disimpan bersama dengan nama pengguna.
- **Login:**
    - Klik "Capture Photo to Login" untuk mengambil gambar.
    - Kode mensimulasikan pencocokan wajah dengan secara acak menentukan kecocokan. (Dalam aplikasi nyata, ini akan melibatkan perbandingan fitur wajah.)
    - Jika "kecocokan" berhasil, pengguna terdaftar acak akan "masuk."

## Keterbatasan

- **Tidak Ada Pengenalan Wajah Sebenarnya:** Ini adalah simulasi dan tidak melakukan pengenalan wajah yang sebenarnya.
- **Pencocokan Sederhana:** Proses "pencocokan" acak untuk tujuan demonstrasi.
- **Penyimpanan Lokal:** Data pengguna hanya disimpan di localStorage browser dan tidak aman atau persisten di seluruh perangkat.

## Perbaikan di Masa Mendatang

- Menerapkan pengenalan wajah yang sebenarnya menggunakan library seperti face-api.js.
- Meningkatkan antarmuka pengguna dan menambahkan lebih banyak fitur.
- Menjelajahi penyimpanan sisi server untuk data pengguna dan keamanan.

## Kontribusi

Jangan ragu untuk melakukan fork repositori dan mengirimkan pull request untuk setiap perbaikan atau perbaikan bug.

## Lisensi

Proyek ini bersifat open-source dan tersedia di bawah Lisensi MIT.
