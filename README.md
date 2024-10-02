# project-dicoding-data-analysis - Dicoding
Project Dicoding "Belajar Data Analisis dengan Python"  dengan dataset E-Commerce

![Project Dicoding "Belajar Data Analisis dengan Python"](thumbnail.mp4)

## Daftar Isi
- [Gambaran Umum](#Gambaran-Umum)
- [Struktur Proyek](#Struktur-Proyek)
- [Instalasi](#Instalasi)
- [Penggunaan](#Penggunaan)
- [Sumber Data](#Sumber-Data)

##  Gambaran Umum
Proyek ini adalah proyek analisis dan visualisasi data yang berfokus pada data publik e-commerce. Proyek ini mencakup kode untuk data wrangling, analisis data eksploratif (EDA), dan dasbor Streamlit untuk eksplorasi data interaktif. Proyek ini bertujuan untuk menganalisis data pada Dataset Publik E-Commerce.

## Struktur Proyek
- `dashboard/`:  Direktori ini berisi dashboard.py yang digunakan untuk membuat dasbor hasil analisis data.
- `data/`: Direktori yang berisi file data CSV mentah.
- `notebook.ipynb`:  File ini digunakan untuk melakukan analisis data.
- `README.md`:  File dokumentasi ini.

## Instalasi
1.  Kloning repositori ini ke mesin lokal Anda:
```
git clone https://github.com/AlexA320/project-dicoding-data-analysis.git
```
2. Pergi ke direktori proyek
```
cd project-dicoding-data-analysis
```
3. Instal paket Python yang diperlukan dengan menjalankan:
```
pip install -r requirements.txt
```

## Penggunaan
1. **Data Wrangling**:  Skrip penguraian data tersedia dalam berkas `notebook.ipynb` untuk menyiapkan dan membersihkan data.

2. **Exploratory Data Analysis (EDA)**: Mengeksplorasi dan menganalisis data menggunakan skrip Python yang disediakan. Wawasan EDA dapat memandu pemahaman Anda tentang pola data publik e-commerce.

3. **Visualization**: Jalankan dasbor Streamlit untuk eksplorasi data interaktif:

```
cd data-analyst-dicoding/dashboard
streamlit run dashboard.py
```
Akses dasbor di peramban/browser web Anda di `http://localhost:8501`.

## Sumber Data
Proyek ini menggunakan E-Commerce Public Dataset dari [Belajar Analisis Data dengan Python's Final Project](https://drive.google.com/file/d/1MsAjPM7oKtVfJL_wRp1qmCajtSG1mdcK/view) yang ditawarkan oleh [Dicoding](https://www.dicoding.com/).
