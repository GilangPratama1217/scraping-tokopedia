# Scraping Data Ulasan Tokopedia - Google Play Store

## Informasi Penelitian
- **Judul:** Analisis Sentimen Ulasan Pengguna Tokopedia pada Google Play Store Menggunakan Algoritma Naïve Bayes dengan Seleksi Fitur Chi-Square
- **Nama:** Gilang Pratama Putra
- **NIM:** 12221899
- **Program Studi:** Informatika S1
- **Institusi:** STMIK El Rahma Yogyakarta
- **Tahun:** 2026

## Deskripsi
Repository ini berisi data hasil scraping ulasan pengguna aplikasi Tokopedia dari Google Play Store yang digunakan sebagai dataset penelitian tugas akhir.

## Sumber Data
Data diambil dari Google Play Store aplikasi Tokopedia:
- **ID Aplikasi:** com.tokopedia.tkpd
- **Link Aplikasi:** https://play.google.com/store/apps/details?id=com.tokopedia.tkpd
- **Jumlah Data:** 2.000 ulasan terbaru
- **Bahasa:** Indonesia
- **Metode Pengambilan:** Web Scraping menggunakan library google-play-scraper (Python)

## Isi Repository
| File | Keterangan |
|------|-----------|
| `Codingan_Naive_Bayes.ipynb` | Notebook Google Colab berisi kode scraping, preprocessing, dan pelatihan model |
| `tokopedia_preprocessed.csv` | Dataset hasil scraping dan preprocessing |

## Cara Penggunaan
1. Buka file `Codingan_Naive_Bayes.ipynb` di Google Colab
2. Jalankan setiap cell secara berurutan
3. Data hasil scraping tersimpan otomatis dalam format CSV
