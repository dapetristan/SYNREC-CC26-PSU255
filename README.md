# [cite_start]SYNREC - Sistem Rekomendasi Film Berbasis Kemiripan Semantik Sinopsis [cite: 6, 7]

![SYNREC Platform](https://synrec.vercel.app/

Sistem rekomendasi film cerdas yang memanfaatkan kecerdasan buatan untuk memberikan rekomendasi berdasarkan makna dan tema cerita, bukan sekadar genre atau riwayat tontonan. [cite_start]Proyek ini merupakan Capstone Project untuk Coding Camp 2026 powered by DBS Foundation (Tim CC26-PSU255)[cite: 2, 3].

## 🚀 Latar Belakang & Solusi
[cite_start]Industri *video streaming* global mengalami pertumbuhan pesat yang memicu fenomena *information overload*, di mana banyaknya pilihan justru menyulitkan pengguna menemukan konten[cite: 23, 26]. [cite_start]Sistem rekomendasi konvensional seringkali gagal memberikan rekomendasi bagi pengguna baru (*cold start problem*) dan tidak bisa menangkap kemiripan tema film yang memiliki genre berbeda[cite: 43, 47].

[cite_start]**SYNREC** hadir sebagai solusi dengan menerapkan pendekatan *Transfer Learning* menggunakan **Sentence-BERT (SBERT)** dan **TensorFlow Functional API**[cite: 48]. [cite_start]Sistem ini mengubah sinopsis film menjadi representasi vektor untuk menghitung tingkat kemiripan semantik antar film, mencatatkan akurasi 89.20% pada *tolerance rating* ±2.0[cite: 51, 66].

## 🔗 Tautan Akses
* [cite_start]**Web Application**: [https://synrec.vercel.app/](https://synrec.vercel.app/) [cite: 154]
* [cite_start]**Data Dashboard**: [Streamlit App](https://movie-recommendation-v3mpy94box2ytktuuqmhbj.streamlit.app/) [cite: 152]
* **Pitching Video**: [Tautan Video YouTube/Unlisted]

## 🏗️ Arsitektur Proyek (Monorepo)
Repository ini memuat seluruh komponen (Full-Stack dan AI) yang saling terintegrasi:

* [cite_start]`/frontend` - Antarmuka pengguna (UI) modern berbasis web[cite: 156].
* [cite_start]`/backend` - RESTful API utama untuk melayani aplikasi web[cite: 83, 157].
* [cite_start]`/model-service` - REST API mandiri (FastAPI/Flask) khusus untuk melayani *inference* model *Machine Learning*[cite: 132, 158].
* [cite_start]`/dashboard` - Dashboard interaktif (Streamlit) berisi hasil *Exploratory Data Analysis* (EDA)[cite: 109, 111, 159].

## 👥 Tim Pengembang (Jawara / MARVIC)
| Nama | Peran | ID Coding Camp |
|---|---|---|
| Wafiq Gifari Putra Yudha | AI Engineer | [cite_start]CACC180D6Y1190 [cite: 14] |
| Muhammad Daffa Tristan | AI Engineer | [cite_start]CACC180D6Y2131 [cite: 14] |
| Deva Rahma Dwi Pricahyanti | Data Scientist | [cite_start]CDCC180D6X1031 [cite: 14] |
| Nabila Habwa Salsabila | Data Scientist | [cite_start]CDCC180D6X2023 [cite: 15] |
| Muhammad Zaky Adinata | Full-Stack Web Developer | [cite_start]CFCC284D6Y1618 [cite: 16] |
| Nur Faiz Darmahidayanto | Full-Stack Web Developer | [cite_start]CFCC939D6Y08050 [cite: 18] |

[cite_start]**Advisor**: Fathul Muiin [cite: 11]

## 🛠️ Tech Stack Utama
* [cite_start]**Artificial Intelligence**: TensorFlow Functional API, SBERT (all-mpnet-base-v2), Custom Callback, tf.GradientTape[cite: 48, 50, 90, 94, 134].
* [cite_start]**Data Science**: Python, Pandas, Streamlit[cite: 111, 146].
* [cite_start]**Full-Stack**: Module Bundler (Vite/Webpack), RESTful API, Networking Calls (Axios)[cite: 80, 81, 83, 128].

## 💻 Panduan Instalasi Lokal (Local Setup)
*Belom*