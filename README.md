# 🌱 Smart Irrigation – AICTE x Shell Internship

This project was developed as part of the **AICTE Internship (Cycle 2)** in collaboration with **Shell**.  
It uses **machine learning** to predict whether irrigation is required based on environmental and crop data, helping farmers save water and improve crop yield.

---

## 🚀 Features
- Predicts **irrigation requirements** using ML models.
- **Model comparison** between **Random Forest** and **XGBoost**.
- Works with environmental factors such as temperature, humidity, and soil moisture.
- Ready-to-use **Flask app** for deployment.
- Jupyter Notebook for training, testing, and evaluation.

---

## 📂 Project Structure

├── app.py # Flask app for predictions

├── irrigation_machine.csv # Dataset with environmental & crop data

├── session1.ipynb # Model training & evaluation notebook

└── README.md # Project documentation


---

## 📊 Dataset
- **File**: `irrigation_machine.csv`
- **Sample Columns**:
  - `temperature` (°C)
  - `humidity` (%)
  - `soil_moisture` (%)
  - `rainfall` (mm)
  - `crop_type`
  - `irrigation_required` (Yes/No – target variable)

Data is preprocessed to handle missing values and encode categorical features before model training.

---

## 🧠 Methodology
1. **Data Preprocessing**:
   - Missing value handling
   - Encoding categorical variables
   - Train-test split

2. **Model Training**:
   - Random Forest Classifier
   - XGBoost Classifier

3. **Evaluation**:
   - Accuracy
   - Precision
   - Recall
   - F1-score

4. **Comparison**:
   - Visual graphs comparing model performance.

---

## ⚙️ Installation & Setup
```bash
# Clone the repository
git clone https://github.com/vishakha-sharma21/SmartIrrigation-AICTE-SHELL.git
cd SmartIrrigation-AICTE-SHELL

# Install dependencies
pip install -r requirements.txt

# Run the Flask app
python app.py

```
# Developed by Vishakha Sharma
