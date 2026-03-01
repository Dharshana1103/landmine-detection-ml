# landmine-detection-ml
Landmine Detection using Machine Learning (KNN, SVM, Random Forest, PCA) based on height and voltage sensor data.

# 🚀 Landmine Detection using Machine Learning

## 📌 Project Overview
This project focuses on detecting and classifying different types of landmines using machine learning techniques. The dataset is based on magnetic anomaly sensor readings, where Voltage and Height measurements are used to predict the Mine Type.

## 📊 Dataset Information
- Total Records: 338
- Features:
  - Voltage (Magnetic field sensor reading)
  - Height (Distance measurement)
  - Soil_Type (6 soil categories)
  - Mine_Type (Target variable – 5 classes)
- Dataset Source: Kaggle – Landmines Dataset

## 🔎 Exploratory Data Analysis (EDA)
- Statistical summary (Mean, Median, Variance, Standard Deviation)
- Mine type distribution analysis
- Soil type distribution
- Correlation analysis
- T-Test and ANOVA
- PCA visualization
- Heatmaps and 3D scatter plots

## 🤖 Machine Learning Models Implemented

The following classification models were trained using Height and Voltage features:

| Model | Test Accuracy |
|-------|--------------|
| K-Nearest Neighbors (KNN) | ~38% |
| Random Forest | ~32% |
| Support Vector Machine (SVM) | ~22% |

## 📉 Observations
- Performance is moderate due to small dataset size.
- Only two numerical features were used for classification.
- Multi-class classification (5 classes) increases complexity.
- Further feature engineering and tuning can improve accuracy.

## 🔮 Future Improvements
- Hyperparameter tuning
- Cross-validation
- Feature engineering
- Testing advanced ensemble models
- Implementing Deep Learning approaches

## 🛠 Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy
- 
## 📁 Project Structure

```
Landmine-Detection-ML/
│
├── data/
│   └── landmines1.csv
│
├── notebook/
│   └── landmine_detection.ipynb
│
├── requirements.txt
└── README.md
## 📌 How to Run the Project

1. Clone the repository:

   git clone[ https://github.com/your-username/Landmine-Detection-ML.git](https://github.com/Dharshana1103/landmine-detection-ml)
  
2. Install required libraries:

   pip install -r requirements

3. Open the Jupyter Notebook:

   Landmine_Ml_code_ipynb

  
## 📬 Author
Dharshana P  
Data Science Student

