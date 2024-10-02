# project-dicoding-data-analysis
Project Dicoding "Belajar Data Analisis dengan Python"  dengan dataset E-Commerce
## Table of Contents
- [Overview](#overview)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Data Sources](#data-sources)

## Overview
Proyek ini adalah proyek analisis dan visualisasi data yang berfokus pada data publik e-commerce. Proyek ini mencakup kode untuk data wrangling, analisis data eksploratif (EDA), dan dasbor Streamlit untuk eksplorasi data interaktif. Proyek ini bertujuan untuk menganalisis data pada Dataset Publik E-Commerce.

## Project Structure
- `dashboard/`:  Direktori ini berisi dashboard.py yang digunakan untuk membuat dasbor hasil analisis data.
- `data/`: Direktori yang berisi file data CSV mentah.
- `notebook.ipynb`:  File ini digunakan untuk melakukan analisis data.
- `README.md`:  File dokumentasi ini.

## Installation
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

## penggunaan
1. **Data Wrangling**:  Skrip penguraian data tersedia dalam berkas `notebook.ipynb` untuk menyiapkan dan membersihkan data.

2. **Exploratory Data Analysis (EDA)**: Mengeksplorasi dan menganalisis data menggunakan skrip Python yang disediakan. Wawasan EDA dapat memandu pemahaman Anda tentang pola data publik e-commerce.

3. **Visualization**: Jalankan dasbor Streamlit untuk eksplorasi data interaktif:

```
cd data-analyst-dicoding/dashboard
streamlit run dashboard.py
```
Access the dashboard in your web browser at `http://localhost:8501`.

## Data Sources
The project uses E-Commerce Public Dataset from [Belajar Analisis Data dengan Python's Final Project](https://drive.google.com/file/d/1MsAjPM7oKtVfJL_wRp1qmCajtSG1mdcK/view) offered by [Dicoding](https://www.dicoding.com/).
