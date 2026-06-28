# 🏃 Human Activity Recognition Using Machine Learning

## 📌 Project Overview

This project focuses on **Human Activity Recognition (HAR)** using Machine Learning techniques. The objective is to classify different human physical activities from wearable sensor data collected using accelerometers and gyroscopes.

The model analyzes sensor readings and predicts activities such as walking, running, jogging, sitting, standing, cycling, climbing stairs, and more.

---

## 🚀 Features

- Data preprocessing and cleaning
- Handling class imbalance through sampling
- Exploratory Data Analysis (EDA)
- Data visualization using Matplotlib and Seaborn
- Feature scaling with RobustScaler
- Label Encoding for categorical variables
- Training multiple Machine Learning models
- Performance evaluation using classification metrics
- Confusion Matrix visualization

---

## 📂 Dataset

The project uses the **mHealth (Mobile Health)** dataset.

The dataset contains:

- Accelerometer sensor readings
- Gyroscope sensor readings
- Multiple body positions
- Activity labels
- Subject information

### Activities Included

- None
- Standing Still
- Sitting and Relaxing
- Lying Down
- Walking
- Climbing Stairs
- Waist Bends Forward
- Frontal Elevation of Arms
- Knees Bending (Crouching)
- Cycling
- Jogging
- Running
- Jump Front & Back

---

## 🛠 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels

---

## 📊 Data Preprocessing

The preprocessing pipeline includes:

- Loading dataset
- Checking missing values
- Removing duplicate records
- Balancing activity classes
- Encoding categorical variables
- Outlier analysis
- Feature scaling using RobustScaler
- Train-Test Split

---

## 🤖 Machine Learning Models

The following algorithms are implemented:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree Classifier

Additional imported models for experimentation:

- Random Forest
- Support Vector Machine (SVM)
- Gaussian Naive Bayes
- Lasso Regression

---

## 📈 Evaluation Metrics

Model performance is evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## 📊 Visualizations

The project includes:

- Activity distribution
- Pie chart of activity classes
- Time-series sensor plots
- Histogram distributions
- Box plots
- Confusion Matrix heatmap

---

## 📁 Project Structure

```
Human-Activity-Recognition/
│
├── mhealth_raw_data.csv
├── Human Activity Recognition.ipynb
├── README.md
└── requirements.txt
```

---

## ▶️ Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Human-Activity-Recognition.git
```

Move into the project directory

```bash
cd Human-Activity-Recognition
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the notebook

```bash
jupyter notebook
```

---

## 📦 Required Libraries

```text
numpy
pandas
matplotlib
seaborn
scikit-learn
statsmodels
```

Install manually

```bash
pip install numpy pandas matplotlib seaborn scikit-learn statsmodels
```

---

## 🎯 Project Workflow

1. Import Libraries
2. Load Dataset
3. Data Cleaning
4. Exploratory Data Analysis
5. Balance Dataset
6. Feature Engineering
7. Encode Labels
8. Scale Features
9. Train-Test Split
10. Model Training
11. Model Evaluation
12. Activity Prediction

---

## 📌 Results

The implemented Machine Learning models successfully classify human activities using wearable sensor data.

The project demonstrates:

- Effective preprocessing techniques
- Good classification performance
- Clear visualization of sensor patterns
- Comparative evaluation of different ML algorithms

---

## 🔮 Future Improvements

- Deploy using Streamlit or Flask
- Hyperparameter optimization
- Deep Learning (LSTM/CNN)
- Real-time activity recognition
- Wearable device integration
- Mobile application deployment

---
