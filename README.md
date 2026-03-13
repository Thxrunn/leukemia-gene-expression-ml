# Leukemia Gene Expression Classification (Machine Learning)

This project demonstrates a machine learning pipeline for classifying leukemia subtypes using gene expression data.

The model predicts whether a patient has:

• **ALL — Acute Lymphoblastic Leukemia**  
• **AML — Acute Myeloid Leukemia**

The dataset contains thousands of gene expression features per patient.

# Project Objective

The goal of this project is to apply machine learning techniques to high-dimensional genomic data in order to:

- classify leukemia subtypes
- identify important genes related to classification
- visualize biological patterns in gene expression data

# Dataset

Dataset: Leukemia Gene Expression Dataset (OpenML)

Features:
- ~7,000 gene expression measurements
- 72 patient samples

Target classes:
- ALL
- AML

# Machine Learning Pipeline

The pipeline includes the following steps:

1. Data loading from OpenML
2. Feature preprocessing
3. Train-test split
4. Model training using **XGBoost**
5. Model evaluation
6. Feature importance analysis
7. PCA dimensionality reduction
8. Feature selection (Top 100 genes)

# Model Performance

Accuracy achieved:

**93.3%**

Evaluation metrics include:

- Confusion Matrix
- Precision
- Recall
- F1 Score

# Key Techniques Used

Machine Learning:
- XGBoost classifier
- Feature importance analysis
- Feature selection

Data Analysis:
- PCA (Principal Component Analysis)
- Gene importance ranking

Visualization:
- Confusion matrix
- PCA clustering
- Gene importance plots

# Project Structure

aml_multiomics_ai/
│
├── notebooks/
│ ├── 01_setup.ipynb
│ └── 02_leukemia_project_clean.ipynb
│
├── data/
│ └── processed/
│
├── results/
│
└── app/

# Technologies Used

Python

Libraries:
- Pandas
- NumPy
- Scikit-Learn
- XGBoost
- Matplotlib
- Seaborn

# Applications

This type of analysis is used in:

- Genomics research
- Cancer subtype classification
- Biomarker discovery
- Precision medicine
- Bioinformatics pipelines

# Author

Tharun Kumar Malla Dinakaran
Computer Science Student  
California State University San Marcos
tharundina@gmail.com
https://www.linkedin.com/in/tharun-kumar-malla-dinakaran/
