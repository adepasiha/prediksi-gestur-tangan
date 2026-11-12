# ✊✋✌️ Prediksi Gestur Tangan: Gunting, Batu, Kertas

## 📌 Deskripsi Proyek
Proyek ini merupakan implementasi Machine Learning menggunakan metode **Convolutional Neural Network (CNN)** untuk memprediksi dan mengklasifikasikan gestur tangan ke dalam tiga kategori, yaitu:
- **Rock (Batu)**
- **Paper (Kertas)**
- **Scissors (Gunting)**

Model dilatih menggunakan dataset gambar gestur tangan untuk mengenali pola dan bentuk tangan sehingga dapat melakukan klasifikasi secara otomatis.

## 🎯 Tujuan
Membangun model CNN yang mampu mengenali dan memprediksi gestur tangan berdasarkan gambar dengan tingkat akurasi yang baik.

## 📂 Dataset
Dataset yang digunakan berasal dari Kaggle:

[Rock-Paper-Scissors Dataset – Kaggle](https://www.kaggle.com/datasets/sanikamal/rock-paper-scissors-dataset)

Dataset terdiri dari tiga kelas:
- Paper
- Rock
- Scissors

Pembagian data:
- Training: 80% (2.016 gambar)
- Validation: 20% (504 gambar)
- Testing: 372 gambar

## 🛠️ Teknologi dan Library
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-learn
- Seaborn
- KaggleHub

## ⚙️ Metode yang Digunakan
Model menggunakan metode **Convolutional Neural Network (CNN)** dengan beberapa tahapan:
1. Pengumpulan dan pemuatan dataset.
2. Analisis dan visualisasi data.
3. Data Augmentation.
4. Normalisasi gambar.
5. Pembuatan arsitektur CNN.
6. Training model.
7. Evaluasi model.
8. Penyimpanan model.

## 📊 Hasil Evaluasi
Berdasarkan hasil pengujian pada data testing, model memperoleh akurasi sekitar **98,66%**.

Model mampu mengklasifikasikan ketiga jenis gestur tangan, yaitu batu, kertas, dan gunting dengan hasil yang baik.

## 💾 File Model
Model yang telah dilatih disimpan dengan nama:

`rps_cnn.keras`

File tersebut berisi arsitektur dan bobot model yang dapat digunakan kembali untuk melakukan prediksi.

## ▶️ Cara Menjalankan
1. Buka notebook menggunakan Kaggle Notebook.
2. Jalankan setiap sel kode secara berurutan.
3. Pastikan dataset berhasil diunduh.
4. Tunggu proses training dan evaluasi selesai.
5. Model akan tersimpan dalam format `.keras`.

## 👨‍💻 Penutup
Proyek ini dibuat sebagai implementasi pembelajaran Machine Learning menggunakan metode CNN dalam pengenalan citra atau gambar gestur tangan.

**Project: Prediksi Gestur Tangan Gunting, Batu, Kertas**
