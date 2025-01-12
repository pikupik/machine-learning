# Machine Learning Projects Repository
## 🚀 Projects Overview

### 1. **Drug Classification**
- **Description**: Classify drugs based on specific features.
- **Files**:
  - `drug_classification/klasifikasi_obat.ipynb`: Jupyter Notebook for training, evaluation, and analysis.
  - `model/knn_klasifikasiObt.pkl`: Pre-trained KNN model for drug classification.
  - `dataset/drug200.csv`: Dataset used for training and testing.

- **How to Use**:
  - Run the Jupyter Notebook: `drug_classification/klasifikasi_obat.ipynb`.
  - Use the pre-trained model:
    ```python
    import joblib

    # Load model
    model = joblib.load('model/knn_klasifikasiObt.pkl')

    # Input data (example)
    testing = {'Age': [35],
          'Sex': [1],
          'BP': [2],
          'Cholesterol': [1],
          'Na_to_K': [4.5]}

    # Make prediction
    prediction = model.predict(testing)
    print(f"Predicted Drug: {prediction}")
    ```

---

## 🛠️ Setup Instructions

1. Clone this repository:
   ```bash
   git clone https://github.com/pikupik/machine-learning.git
   cd your-repo
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Navigate to the project folder and explore its notebooks or use pre-trained models.

4. Use models
# Muat model
loaded_model = joblib.load("model_rf.joblib")
print("Model berhasil dimuat kembali")

# Contoh prediksi
predictions = loaded_model.predict(X_test)
print(predictions)


---

## 📊 Pre-trained Models
All pre-trained models are stored in the `model/` folder. Use them directly in your scripts without retraining. 

---

## 📝 License
MIT License
