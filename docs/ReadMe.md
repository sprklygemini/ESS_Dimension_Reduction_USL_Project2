# ESS Dimension Reduction Analysis
# Author: Rana Al shwayat

## Project Overview

This project applies dimension reduction techniques to the European Social Survey (ESS) Round 11 dataset to analyze high-dimensional survey data. The goal is to reduce the number of variables while preserving the most important information in the dataset.

Using Principal Component Analysis (PCA), the analysis identifies the main components that explain variance in socio-economic and attitudinal variables. Dimension reduction helps simplify complex datasets, improve visualization, and support downstream machine learning tasks.

Dataset source: https://www.europeansocialsurvey.org

---

## Repository Structure

ESS_Dimension_Reduction_Project
│
├── data/                         # Dataset files (not included due to size)
├── docs/                         # ESS dataset documentation
├── ESS_Dimension_Reduction_Project2.ipynb
└── README.md

---

## Methods Used

- Data preprocessing and feature scaling  
- Principal Component Analysis (PCA)  
- Exploratory data analysis  
- Visualization of principal components  

---

## Tools and Libraries

- Python
- Jupyter Notebook
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

---

## Notes

The raw ESS dataset is not included in this repository due to file size limitations.  
To reproduce the analysis, download the dataset from the official European Social Survey website and place it in the `data/` folder.