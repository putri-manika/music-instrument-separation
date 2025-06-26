# Analisis dan Pengolahan Sinyal Digital dari Instrumen Musik: Pemisahan Audio Dua Instrumen dari Rekaman

## Deskripsi Proyek
Proyek ini bertujuan untuk menganalisis dan mengolah sinyal digital dari rekaman musik, dengan fokus utama pada pemisahan dua suara instrumen dari satu berkas audio campuran. Dalam banyak rekaman musik, suara berbagai instrumen terekam dalam satu saluran, sehingga diperlukan teknik pemrosesan sinyal untuk mengisolasi suara tertentu.

Melalui pendekatan seperti transformasi frekuensi (PSD) dan teknik visualisasi spektrum, proyek ini menjadi alat bantu yang potensial bagi musisi atau peneliti untuk:

Mengidentifikasi karakteristik frekuensi tiap instrumen

Memahami struktur suara dalam campuran audio

Meningkatkan kemampuan belajar dan latihan melalui analisis isolasi suara

## Library
Notebook ini dibangun dengan Python menggunakan library berikut:

- numpy — operasi numerik

- scipy.signal — perhitungan Power Spectral Density (PSD)

- matplotlib — visualisasi spektrum

- librosa — pemrosesan sinyal audio

- IPython.display — untuk memutar audio di notebook

## Metodologi Utama
1. Preprocessing Audio

2. Pembacaan file WAV menggunakan librosa

3. Normalisasi sinyal audio

4. Analisis Power Spectral Density (PSD)

5. Menggunakan scipy.signal.welch untuk menampilkan sebaran daya terhadap frekuensi

6. Membandingkan spektrum dua instrumen yang dicampur

7. Visualisasi

8. Plot domain waktu dan domain frekuensi

9. Analisis puncak spektrum sebagai indikasi kehadiran instrumen dominan

10. Simulasi Pemisahan (baseline)

11. Analisis sinyal campuran untuk menduga bagian sinyal yang dominan dari satu instrumen

## Tujuan Akhir
- Membuat dasar model pemisahan sinyal audio dua instrumen

- Memberikan insight tentang pola spektral khas instrumen seperti bass dan biola

- Mengembangkan metode lanjutan (di luar notebook ini) seperti Independent Component Analysis (ICA) atau Non-negative Matrix Factorization (NMF) sebagai kelanjutan

## Struktur File
PSD_Progress2.ipynb — Notebook utama berisi analisis dan eksperimen

audio/ — Folder (opsional) tempat menyimpan file audio masukan

## Kontributor 
- Putri Manika Rukmamaya (23031554091)

- Monika Intan Puspitasari (23031554189)

- Sintiya Risla Miftakhul Nikmah (23031554204)
