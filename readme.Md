# KNN Model for Classification

This repository contains a pre-trained K-Nearest Neighbors (KNN) classification model. The model can be used to classify data based on features. Below are the instructions to use the model.

---

## 📂 Files in This Repository
- **`knn_model.pkl`**: The pre-trained KNN model serialized with `joblib`.
- **`requirements.txt`**: The list of dependencies required to use the model.
- **`example_usage.py`**: A Python script that demonstrates how to load and use the model for predictions.

---

## 🛠️ Requirements
To use this project, make sure you have the following installed:
- Python 3.7 or above
- Required libraries listed in `requirements.txt`

You can install the dependencies with:
```bash
pip install -r requirements.txt
```

---

## 🚀 How to Use the Model

1. **Clone this repository**:
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
   ```

2. **Load the model in your Python script**:
   Here's an example of how to use the pre-trained model:
   ```python
   import joblib

   # Load the model
   model = joblib.load('knn_klasifikasiObt.pkl')

   # Input data (example)
   testing = {'Age': [35],
          'Sex': [1],
          'BP': [2],
          'Cholesterol': [1],
          'Na_to_K': [4.5]}

   # Make a prediction
   prediction = model.predict(testing)

   print(f"Predicted class: {prediction}")
   ```

3. **Run the example script**:
   To see the model in action, run the provided example script:
   ```bash
   python example_usage.py
   ```

---

## 📊 Model Details
- **Algorithm**: K-Nearest Neighbors (KNN)
- **Hyperparameters**: `n_neighbors=3`
- **Accuracy**: 77%

improve the accuracy for more datasets

---

## 📝 License
MIT License