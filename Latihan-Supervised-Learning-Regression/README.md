# Latihan Supervised Learning – Regression

Repository ini berisi latihan dan eksperimen **Supervised Learning (Regression)** menggunakan Python dan library data science populer. Fokus utama proyek ini adalah memahami alur kerja pemodelan regresi, evaluasi model, serta interpretasi hasil.

## Tujuan
- Mempelajari dan membandingkan beberapa algoritma regresi
- Memahami metrik evaluasi regresi (MAE, MSE, R²)
- Melatih intuisi dalam memilih model berdasarkan karakteristik data

## Dataset
Dataset yang digunakan **tidak disertakan di dalam repository** karena ukuran file yang besar.

Sumber dataset:
- **Kaggle – Playground Series Season 4 Episode 5**  
  https://www.kaggle.com/competitions/playground-series-s4e5/data

Dataset ini digunakan sebagai data latih untuk eksperimen regresi.

## Cara Menggunakan Dataset
1. Unduh dataset dari link Kaggle di atas
2. Ekstrak file dan buat folder `data/` di root project
3. Letakkan file dataset (misalnya `train.csv`) ke dalam folder `data/`

Struktur direktori yang diharapkan:
```text
Latihan-Supervised-Learning-Regression/
├── data/
│   └── train.csv
├── notebook.ipynb
├── README.md
````

> Folder `data/` di-*ignore* oleh Git untuk menjaga ukuran repository tetap ringan.

## Model yang Digunakan

Beberapa model regresi yang digunakan dalam latihan ini:

* Linear Regression
* Lars
* Gradient Boosting Regressor

Evaluasi dilakukan menggunakan:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Coefficient of Determination (R²)

## Catatan

Repository ini bertujuan sebagai **media belajar dan dokumentasi eksperimen**, bukan sebagai submission resmi kompetisi Kaggle.

---

📌 *Latihan ini menekankan bahwa model sederhana sering kali memberikan performa terbaik ketika struktur data cenderung linear.*

