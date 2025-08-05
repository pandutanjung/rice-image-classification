# Rice Image Classification

## Deskripsi Proyek
Proyek ini bertujuan untuk mengklasifikasikan jenis-jenis padi berdasarkan gambar daun padi menggunakan metode pembelajaran mesin (machine learning). Dataset yang digunakan terdiri dari gambar-gambar daun padi dengan label kelas tertentu. Model yang dibangun bertujuan untuk membantu dalam identifikasi jenis padi secara otomatis.

## Fitur Utama
- Preprocessing gambar daun padi
- Training model klasifikasi menggunakan Convolutional Neural Network (CNN)
- Evaluasi performa model menggunakan metrik akurasi dan confusion matrix
- Visualisasi hasil prediksi dan metrik evaluasi

## Dataset
Dataset berupa kumpulan gambar daun padi yang sudah diberi label jenis padi masing-masing. Dataset ini digunakan untuk melatih dan menguji model.

## Teknologi dan Library
- Python 3.x
- TensorFlow / Keras
- NumPy
- Matplotlib
- scikit-learn
- Jupyter Notebook

## Cara Menjalankan Proyek
1. Clone repository ini atau download file notebook `Rice_Image_Classification.ipynb`.
2. Pastikan semua dependensi sudah terinstall, misalnya dengan menjalankan:
   ```bash
   pip install -r requirements.txt
   ```
3. Jalankan notebook `Rice_Image_Classification.ipynb` pada Jupyter Notebook atau Jupyter Lab.
4. Ikuti langkah-langkah preprocessing, training, dan evaluasi pada notebook.

## Struktur Proyek
```
├── Rice_Image_Classification.ipynb   # Notebook utama proyek
├── dataset/                          # Folder berisi data gambar padi (jika tersedia)
├── requirements.txt                  # Daftar library yang dibutuhkan
└── README.md                         # Dokumentasi proyek
```

## Hasil dan Evaluasi
Model mampu mengklasifikasikan jenis padi dengan akurasi yang baik. Grafik dan confusion matrix dapat ditemukan di notebook sebagai bahan evaluasi.

## Lisensi
Proyek ini menggunakan lisensi MIT (atau sesuai kebutuhan).
