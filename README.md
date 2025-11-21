# Perbandingan Vision Transformer: Swin vs DeiT vs MAE

## Deskripsi Proyek

Proyek ini bertujuan untuk membandingkan kinerja tiga model Vision Transformer (ViT) populer dalam tugas klasifikasi citra menggunakan **Flowers Dataset**. Model yang dibandingkan adalah:

1.  **Swin Transformer** (Hierarchical Vision Transformer)
2.  **DeiT** (Data-efficient Image Transformer)
3.  **MAE** (Masked Autoencoder)

Analisis mencakup akurasi, presisi, recall, F1-score, ukuran model, dan kecepatan inferensi.

## Struktur Direktori

- `vision_transformer_comparison.ipynb`: Notebook utama berisi kode eksperimen.
- `flowers-dataset/`: Direktori dataset (akan diunduh otomatis).
- `results/`: Direktori output untuk menyimpan metrik, model, dan log pelatihan.
- `laporan/`: Dokumen laporan proyek (LaTeX).

## Persyaratan Sistem

- Python 3.x
- Jupyter Notebook / VS Code
- Koneksi internet (untuk mengunduh dataset via `kagglehub` dan model pre-trained).

## Cara Menjalankan

### 1. Instalasi Dependensi

Pastikan Anda berada di direktori root proyek, lalu jalankan perintah berikut untuk menginstal library yang dibutuhkan:

```bash
pip install -r requirements.txt
```

### 2. Menjalankan Eksperimen

Buka file `vision_transformer_comparison.ipynb` menggunakan Jupyter Notebook atau Visual Studio Code.
Jalankan semua sel secara berurutan.

## Hasil

Hasil eksperimen akan disimpan secara otomatis di folder `results/`, meliputi:

- `comprehensive_comparison.csv`: Perbandingan lengkap semua metrik.
- `performance_metrics.csv`: Metrik evaluasi (Akurasi, F1, dll).
- `inference_times.csv`: Data kecepatan inferensi.
- `model_parameters.csv`: Ukuran dan jumlah parameter model.
- File model (`.pth`) dan riwayat pelatihan (`.json`).
