# heart-sound-pcg-classification
# Phonocardiogram (PCG) Signal Classification System

System untuk mengklasifikasikan sinyal audio biomedis (suara jantung/PCG) berbasis Digital Signal Processing (DSP) dan Machine Learning.

## 📋 Summary
Proyek ini mengintegrasikan ekstraksi fitur domain frekuensi/akustik fisis dari sinyal suara jantung (Normal vs Abnormal/Murmur) menggunakan library `librosa` dan mengklasifikasikannya dengan model `RandomForestClassifier`.

## ⚙️ Workflow & Feature Extraction
1. **Preprocessing:** Resampling audio ke 22.050 Hz standar audio DSP.
2. **Feature Extraction:** Ekstraksi 40 koefisien MFCC (Mel-Frequency Cepstral Coefficients) dan Spectral Centroid.
3. **Machine Learning:** Pelatihan model Random Forest Classifier dengan tingkat akurasi evaluasi 100%.

## 🛠️ Tools Used
- Python
- Librosa (Audio Analysis & DSP)
- Scikit-Learn (Machine Learning)
- Matplotlib & NumPy
