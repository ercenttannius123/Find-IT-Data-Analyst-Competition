# FindIT - Face Liveness Detection Project

Proyek machine learning untuk mendeteksi dan mengklasifikasi keaslian wajah manusia dalam foto/video menggunakan deep learning. Project ini dikembangkan untuk **Data Analytics Competition 2026 - Find It**.

## 📋 Deskripsi Proyek

FindIT adalah sistem klasifikasi image yang dapat membedakan antara:
- **Real Person**: Wajah asli manusia
- **Fake Printed**: Wajah dari foto yang dicetak
- **Fake Screen**: Wajah dari layar monitor/gadget
- **Fake Mask**: Wajah menggunakan topeng/muka palsu
- **Fake Mannequin**: Wajah dari boneka/patung
- **Fake Unknown**: Jenis penipuan wajah lainnya

## 🎯 Tujuan

Mengembangkan model machine learning yang akurat dalam mendeteksi liveness (keaslian) wajah untuk mencegah penipuan biometrik.

## 📊 Dataset

Dataset diambil dari **Kaggle Competition**: Data Analytics Competition DAC - Find It 2026

- **Training Data**: ~6,000 gambar terklasifikasi dalam 6 kelas
- **Test Data**: Gambar test untuk evaluasi model

## 🛠️ Teknologi & Library

- **Python 3.x**
- **TensorFlow / Keras** - Deep learning framework
- **PyTorch** - Alternative framework
- **OpenCV** - Image processing
- **NumPy & Pandas** - Data manipulation
- **Matplotlib & Seaborn** - Visualization
- **Scikit-learn** - ML utilities
- **Albumentations** - Image augmentation
- **Timm** - Pre-trained models

## 🚀 Instalasi & Setup

### Prerequisites
- Python 3.7+
- pip atau conda
- Kaggle API credentials

### Langkah 1: Clone Repository
```bash
git clone <repository-url>
cd "DAC Lomba"
```

### Langkah 2: Install Dependencies
```bash
pip install -r requirements.txt
```

### Langkah 3: Setup Kaggle API
1. Buat akun di [Kaggle](https://www.kaggle.com)
2. Download `kaggle.json` dari settings
3. Upload file saat menjalankan notebook

### Langkah 4: Download Dataset
Dataset akan otomatis didownload menggunakan Kaggle API saat menjalankan notebook.

## 📖 Struktur Proyek

```
FindIT_Project_Improved_(2).ipynb
├── 1. Setup & Data Loading
│   └── Install dependencies, setup Kaggle API
├── 2. Data Exploration
│   └── Analisis distribusi kelas dan visualisasi
├── 3. Data Preprocessing
│   └── Augmentasi dan normalisasi gambar
├── 4. Model Development
│   └── Training berbagai model (CNN, Transfer Learning, dll)
├── 5. Model Evaluation
│   └── Testing dan evaluasi performance
└── 6. Predictions
    └── Generate submission file
```

## 🔄 Workflow

1. **Setup**: Install packages dan setup Kaggle API
2. **Data Loading**: Download dan extract dataset
3. **EDA**: Exploratory data analysis dan visualisasi
4. **Preprocessing**: Augmentasi dan normalisasi data
5. **Modeling**: Train berbagai model architecture
6. **Evaluation**: Validasi dan testing
7. **Submission**: Generate file prediksi untuk kompetisi

## 📈 Model Architecture

Proyek menggunakan:
- **Convolutional Neural Networks (CNN)**
- **Transfer Learning** (pre-trained models dari timm)
- **Ensemble Methods** (kombinasi multiple models)

## 🎓 Features

✅ Data exploration dan visualization
✅ Image augmentation dengan albumentations
✅ Multiple model architectures
✅ Cross-validation dan hyperparameter tuning
✅ Performance metrics visualization
✅ Model ensembling
✅ Competition submission format

## 📊 Expected Outcomes

Model yang dapat mengklasifikasi dengan akurasi tinggi:
- Validasi accuracy
- Precision, recall, dan F1-score per kelas
- Confusion matrix visualization

## 👥 Contributors

- Ercent Tannius
- Erica Patricia Susanto
- Winson Jonathan
- DAC Competition 2026

## 📝 License

Private - Untuk keperluan akademis

## 📞 Support

Untuk pertanyaan atau issues, silakan buat issue di repository ini.

## 🔗 Resources

- [Kaggle Competition](https://www.kaggle.com/competitions/data-analytics-competition-dac-find-it-2026-resubmissio)
- [OpenCV Documentation](https://docs.opencv.org/)
- [TensorFlow Documentation](https://www.tensorflow.org/)
- [Timm Models](https://github.com/rwightman/pytorch-image-models)

---

**Last Updated**: April 2026
**Status**: Active Development
