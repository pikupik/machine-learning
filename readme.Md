# Machine Learning Projects Repository

This repository contains various machine learning projects, including **Drug Classification** and **Crypto Market Analysis**. Each project has its own datasets, trained models, and Jupyter Notebooks for training and evaluation. You can choose which project to use based on your needs.
---

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

### 2. **Crypto Market Analysis**
- **Description**: Perform market analysis and generate trading signals for Bitcoin using technical indicators.
- **Files**:
  - `crypto_analyst/crypto_analyst.ipynb`: Jupyter Notebook for market analysis and visualization.
  - `dataset/crypto_data.csv`: Historical crypto market data.

- **How to Use**:
  - Run the Jupyter Notebook: `crypto_analyst/crypto_analyst.ipynb`.
  - Explore trading signals, RSI, Bollinger Bands, and MACD indicators.

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

---

## 📊 Pre-trained Models
All pre-trained models are stored in the `model/` folder. Use them directly in your scripts without retraining. 

---

## 📝 License
MIT License
