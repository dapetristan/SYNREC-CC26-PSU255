### 🎞️ SYNREC - Sistem Rekomendasi Film Berbasis Kemiripan Semantik Sinopsis 🎞️

![SYNREC Platform]!
(https://synrec.vercel.app/)

SYNREC adalah sistem rekomendasi film cerdas yang memanfaatkan kecerdasan buatan untuk memberikan rekomendasi berdasarkan makna dan tema cerita, bukan sekadar genre atau riwayat tontonan. Proyek ini mengusung tema Future-Ready Work & Economy dengan mengimplementasikan teknik Transfer Learning berbasis Sentence-BERT (SBERT) dan TensorFlow Functional API. SYNREC memungkinkan pengguna untuk menemukan film dengan tema, konflik, atau suasana naratif yang serupa, dengan memanfaatkan kemiripan sinonsis cerita.

## 🚀 Latar Belakang & Solusi
Industri *video streaming* global mengalami pertumbuhan pesat yang memicu fenomena *information overload*, di mana banyaknya pilihan justru menyulitkan pengguna menemukan konten. Sistem rekomendasi konvensional seringkali gagal memberikan rekomendasi bagi pengguna baru (*cold start problem*) dan tidak bisa menangkap kemiripan tema film yang memiliki genre berbeda.

**SYNREC** hadir sebagai solusi dengan menerapkan pendekatan *Transfer Learning* menggunakan **Sentence-BERT (SBERT)** dan **TensorFlow Functional API**. Sistem ini mengubah sinopsis film menjadi representasi vektor untuk menghitung tingkat kemiripan semantik antar film, dengan memberikan akurasi sebesar 89.20% pada *tolerance rating* ±2.0

## 🔗 Tautan Akses
* **Web Application**: (https://synrec.vercel.app/)
* **Data Dashboard**: (https://movie-recommendation-v3mpy94box2ytktuuqmhbj.streamlit.app/)
* **Pitching Video**: [Tautan Video YouTube/Unlisted]

## 🏗️ Arsitektur Proyek (Monorepo)
Repository ini memuat seluruh komponen (Full-Stack dan AI) yang saling terintegrasi:

* `/frontend` - Antarmuka pengguna (UI) modern berbasis web
* `/backend` - RESTful API utama untuk melayani aplikasi web
* `/model-service` - REST API mandiri (FastAPI/Flask) khusus untuk melayani *inference* model *Machine Learning*
* `/dashboard` - Dashboard interaktif (Streamlit) berisi hasil *Exploratory Data Analysis* (EDA)

## 👥 Tim Pengembang
| Nama | Peran | ID Coding Camp |
|---|---|---|
| Wafiq Gifari Putra Yudha | AI Engineer | [cite_start]CACC180D6Y1190 |
| Muhammad Daffa Tristan | AI Engineer | [cite_start]CACC180D6Y2131 |
| Deva Rahma Dwi Pricahyanti | Data Scientist | [cite_start]CDCC180D6X1031 |
| Nabila Habwa Salsabila | Data Scientist | [cite_start]CDCC180D6X2023 |
| Muhammad Zaky Adinata | Full-Stack Web Developer | [cite_start]CFCC284D6Y1618 |
| Nur Faiz Darmahidayanto | Full-Stack Web Developer | [cite_start]CFCC939D6Y08050 |

**Advisor**: Fathul Muiin

## 🛠️ Tech Stack Utama
* **Artificial Intelligence**: TensorFlow Functional API, SBERT (all-mpnet-base-v2), Custom Callback, tf.GradientTape
* **Data Science**: Python, Pandas, Streamlit
* **Full-Stack**: Module Bundler (Vite/Webpack), RESTful API, Networking Calls (Axios)

## 💻 Panduan Instalasi Lokal (Local Setup)
*Belom*
