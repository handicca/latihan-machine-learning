# Latihan Machine Learning

Repository ini berisi kumpulan latihan **Machine Learning** yang disusun secara bertahap untuk memahami konsep dasar hingga penerapan praktis menggunakan Python. Setiap folder merepresentasikan satu topik utama dalam machine learning dan berisi eksperimen, notebook, serta catatan pembelajaran.

Tujuan utama repo ini adalah membangun pemahaman konseptual yang kuat, bukan sekadar menjalankan kode.

---

## Struktur Repository

```text
LATIHAN-MACHINE-LEARNING/
├── Latihan-Supervised-Learning-Classification/
│   └── notebook-classification.ipynb
├── Latihan-Supervised-Learning-Regression/
│   ├── notebook-regression.ipynb
│   └── README.md
├── Latihan-Unsupervised-Learning-Clustering/
│   └── notebook-clustering.ipynb
├── main.py
├── pyproject.toml
├── uv.lock
├── .python-version
├── .gitignore
└── README.md
````

---

## Topik yang Dipelajari

### 1️⃣ Supervised Learning – Classification

Latihan ini berfokus pada permasalahan klasifikasi, termasuk:

* Konsep supervised learning
* Perbedaan fitur, label, dan target
* Evaluasi model klasifikasi
* Interpretasi hasil prediksi

Model dan teknik yang digunakan disesuaikan dengan tujuan pembelajaran, bukan optimasi kompetisi.

---

### 2️⃣ Supervised Learning – Regression

Latihan ini membahas prediksi nilai kontinu menggunakan regresi.

Cakupan materi:

* Linear Regression
* Lars
* Gradient Boosting Regressor
* Evaluasi menggunakan MAE, MSE, dan R²
* Analisis dan perbandingan performa model

Dataset yang digunakan berasal dari Kaggle dan **tidak disertakan di repository** karena ukuran besar.
Detail dataset dan cara penggunaannya dijelaskan di README pada folder regresi.

---

### 3️⃣ Unsupervised Learning – Clustering

Latihan clustering difokuskan pada:

* Konsep unsupervised learning
* KMeans dan algoritma clustering lainnya
* Penentuan jumlah cluster
* Interpretasi cluster dan visualisasi

Latihan ini menekankan pemahaman pola data tanpa label.

---

## Environment & Tools

Repository ini menggunakan:

* **Python**
* **Jupyter Notebook**
* **NumPy, Pandas, Matplotlib, Scikit-learn**
* **uv** sebagai dependency manager

File penting:

* `pyproject.toml` → konfigurasi dependensi
* `uv.lock` → lock file environment
* `.python-version` → versi Python yang digunakan

---

## Catatan Penting

* Folder `data/` tidak disertakan di repository untuk menjaga ukuran repo tetap ringan
* Dataset eksternal dijelaskan dan ditautkan pada masing-masing README latihan
* Repository ini ditujukan untuk **pembelajaran dan dokumentasi progres**, bukan submission kompetisi

---

## Tujuan Jangka Panjang

* Membangun intuisi pemilihan model
* Memahami kapan model sederhana lebih efektif daripada model kompleks
* Membiasakan workflow machine learning yang rapi dan reproducible

---

📌 *Machine learning bukan tentang model tercanggih, tapi tentang pemahaman data dan keputusan yang masuk akal.*