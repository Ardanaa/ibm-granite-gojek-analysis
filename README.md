# Gojek Review Analysis

Analisis sentimen dan ringkasan otomatis terhadap ulasan pengguna aplikasi Gojek dari Google Play Store menggunakan model AI IBM Granite. Proyek ini merupakan bagian dari Capstone Project dalam program Student Development Initiative.

## 📌 Project Overview

Ulasan pengguna dapat menjadi sumber insight berharga untuk pengembangan produk dan layanan digital. Dalam proyek ini, dilakukan analisis terhadap 91 ulasan valid aplikasi Gojek menggunakan model AI IBM Granite untuk:

- Mengklasifikasikan sentimen (positif, negatif, netral)
- Merangkum isi ulasan untuk menemukan topik utama

Tujuannya adalah untuk menemukan pola keluhan dan pujian dari pengguna serta memberikan rekomendasi berbasis data.

## 🗂 Dataset

Dataset terdiri dari 100 ulasan pengguna aplikasi Gojek dari Google Play Store, dengan 91 ulasan yang valid digunakan dalam analisis. Kolom dalam yg digunakan:
- `content`: Isi ulasan

## 🔍 Insight & Findings
<img width="1672" height="587" alt="image" src="https://github.com/user-attachments/assets/60d35491-8a9d-490d-a9ae-35cf4767b7ba" />


### Distribusi Sentimen:
- **Positif**: 65.9%
- **Negatif**: 27.5%
- **Netral**: 6.6%

### Topik Pujian (Sentimen Positif):
- Didominasi oleh aspek **kualitas aplikasi**, seperti:
  - Kinerja aplikasi yang baik
  - Kemudahan penggunaan
  - Layanan driver yang memuaskan
  - Promo menarik

<img width="1730" height="605" alt="image" src="https://github.com/user-attachments/assets/f5816d0f-de55-458b-8bd9-653fdc13b40c" />

### Topik Keluhan (Sentimen Negatif):
- Mayoritas keluhan berasal dari:
  - **Crash / error aplikasi**
  - **Kualitas layanan driver**
  - **Masalah pada Gopay, top-up, transaksi, suspensi akun**

<img width="1724" height="658" alt="image" src="https://github.com/user-attachments/assets/7f18427f-2f66-4f0d-b6d3-a18d5586b825" />

### Wordcloud
- Berikut gambaran umum kata-kata paling sering muncul pada ulasan pengguna:

<img width="978" height="525" alt="image" src="https://github.com/user-attachments/assets/14b8831e-0d05-4f2f-b63e-62e939276239" />


### Ringkasan Temuan:
- **Aspek paling dihargai pengguna**: *Kualitas*
- **Keluhan utama yang perlu dibenahi**: *Masalah aplikasi & layanan driver*

## 💡 Rekomendasi Strategis

- **Perkuat**: Pertahankan dan promosikan keunggulan pada aspek **kualitas**
- **Perbaiki**: Fokuskan sumber daya untuk menyelesaikan masalah terkait **error aplikasi** dan **layanan driver**

## 🧠 AI Support Explanation

Model **IBM Granite** digunakan untuk dua tugas utama:

1. **Sentiment Classification**  
   Mengelompokkan ulasan ke dalam kategori *positif*, *negatif*, atau *netral* secara otomatis

2. **Summarization**  
   Meringkas isi ulasan menjadi kalimat pendek yang mewakili inti ulasan  
   Membantu mengidentifikasi topik utama dalam waktu singkat

Seluruh proses dijalankan melalui **Google Colab**. Integrasi model dengan API melalui **Replicate**.

## 📎 Colab Notebook

🔗 [Link ke Google Colab Notebook](https://colab.research.google.com/drive/10nNyw-sAy4m3xtwOtl3-X6U8ugy5XJ-w#scrollTo=ZrbzyfFlwcRF)

## 📊 Visualisasi

- Distribusi sentimen
- Wordcloud (positif & negatif)
- Topik keluhan dan pujian (bar chart)
- Ringkasan insight & rekomendasi

## 📌 Kesimpulan

- Mayoritas pengguna puas dengan kualitas aplikasi
- Namun, ada keluhan signifikan terkait error aplikasi & layanan driver
- IBM Granite sangat membantu dalam proses klasifikasi dan peringkasan ulasan
- Insight yang diperoleh mendukung pengambilan keputusan berbasis data

---

