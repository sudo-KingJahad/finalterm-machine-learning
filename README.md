# 🚀 Finalterm Machine Learning Exam: Machine Learning Portfolio

![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange)
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-TensorFlow-red)
![CNN](https://img.shields.io/badge/CNN-Convolutional%20Neural%20Network-purple)

---

## 👤 Student Identification

- **Name**: Kukuh Lintang Fajar  
- **NIM**: 1103220094  
- **Class**: TK-46-03  

🔗 **Output & Results**  
- For 1 & 2: https://drive.google.com/drive/folders/1qHKbK29AyU2OWgBrH5V_dzw3fAzizyvO?usp=sharing
- For 3    : https://drive.google.com/drive/folders/1w3pM9_XETPARafGss3TMj348U-1MCTgm?usp=sharing

---

## 📝 Repository Purpose

This repository is submitted to fulfill the **Final Term Exam requirements** for the **Machine Learning** course.  
The primary objective is to demonstrate the ability to design and implement **end-to-end machine learning pipelines** across multiple problem domains, including **regression, clustering, and classification**, with proper data preprocessing, model selection, evaluation, and result interpretation.

---

## 📚 Project Overview & Technical Description

### 1️⃣ Regression – Song Year Prediction  
📓 **Notebook**: `finalterm_regresi.ipynb`

#### Objective  
Predict the release year of a song based on numerical audio features extracted from signal and timbre characteristics.

#### Dataset  
- `midterm-regresi-dataset.csv`  
- Contains multiple continuous audio-related features.

#### Methodology  
- **Preprocessing**:
  - Handling missing values using mean imputation
  - Feature scaling using `StandardScaler`
- **Model**:
  - Ridge Regression (L2 Regularization) to handle multicollinearity
- **Rationale**:
  - Regularization stabilizes coefficient estimation when features are highly correlated.

#### Evaluation Metrics  
- Root Mean Squared Error (RMSE)  
- R² Score  

---

### 2️⃣ Clustering – Customer Segmentation  
📓 **Notebook**: `finalterm_transaction_data.ipynb`

#### Objective  
Group credit card customers into distinct segments based on spending and payment behavior patterns.

#### Dataset  
- `clusteringmidterm.csv`

#### Methodology  
- **Preprocessing**:
  - Removal of identifier columns
  - Handling missing values
  - Feature scaling using `StandardScaler`
- **Model**:
  - K-Means Clustering
- **Optimal Cluster Selection**:
  - Elbow Method
- **Visualization**:
  - Principal Component Analysis (PCA) for 2D cluster representation

#### Results  
- Customers are grouped into several behavioral segments
- Each cluster represents a distinct usage profile, such as high spenders or installment-focused users

---

### 3️⃣ Classification – Fish Image Detection using CNN  
📓 **Notebook**: `Fish_Image_Detection?.ipynb`

#### Objective  
Develop a multi-class image classification system capable of recognizing different fish species using Convolutional Neural Networks (CNN).

#### Dataset  
- Fish image dataset organized in directory-based class folders
- Separate training, validation, and testing sets

#### Methodology  
- **Preprocessing**:
  - Image resizing to 224×224 pixels
  - RGB color normalization
- **Data Augmentation**:
  - Rotation, zoom, shifting, and horizontal flipping
- **Model Architecture**:
  - Custom CNN built from scratch using:
    - Convolutional layers
    - Batch Normalization
    - Max Pooling
    - Dropout for regularization
- **Handling Class Imbalance**:
  - Computation and application of class weights during training
- **Evaluation**:
  - Accuracy on validation and test datasets
  - Prediction probability distribution for interpretability

#### Results  
- The CNN model successfully learns discriminative visual features of fish images
- Probability distribution plots demonstrate the model’s decision process across classes

---

## 📂 Repository Structure
How to navigate this repository:

```text
finalterm-machine-learning/
│
├── 📓 finalterm_transaction_data.ipynb
├── 📓 finalterm_regresi.ipynb
├── 📓 Fish_Image_Detection.ipynb
├── 📄 README.md
```

---

## ✅ Key Learning Outcomes

- Design and implementation of end-to-end machine learning pipelines  
- Handling imbalanced datasets in classification tasks  
- Application of regression models with regularization  
- Development of CNN-based image classification systems  
- Proper model evaluation and result interpretation  

---

## 📌 Notes

This repository focuses on **methodological correctness and pipeline completeness** rather than solely optimizing performance metrics, in accordance with standard machine learning practices.
