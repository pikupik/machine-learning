# Repositori Proyek Machine Learning
## 🚀 Tinjauan Proyek

### 1. **Klasifikasi Obat (KNN)**
- **Deskripsi**: Mengklasifikasikan obat berdasarkan fitur-fitur tertentu.

### 2. **Pemeriksaan Email Spam (LogisticRegression)**
- **Deskripsi**: Mengklasifikasikan email spam berdasarkan fitur-fitur tertentu.

### 3. **Diabetes (SVM)**
- **Deskripsi**: Mengklasifikasikan diabetes berdasarkan fitur-fitur tertentu.

---

## 🛠️ Petunjuk Setup

1. Clone repositori ini:
   ```bash
   git clone https://github.com/pikupik/machine-learning.git
   cd nama-repo-anda
   ```

2. Pasang dependensi:
   ```bash
   pip install -r requirements.txt
   ```

3. Akses folder proyek dan jelajahi notebooknya atau gunakan model-model yang sudah dilatih sebelumnya.

4. Gunakan model-model
# Muat model
loaded_model = joblib.load("model_rf.joblib")
print("Model berhasil dimuat")

# Contoh prediksi
predictions = loaded_model.predict(X_test)
print(predictions)

---

## 📊 Model-model Pre-trained
Semua model pre-trained tersimpan di folder `model/`. Gunakan langsung dalam skrip Anda tanpa perlu pelatihan ulang.

## 📝 Lisensi
MIT License