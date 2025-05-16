# Laptop Price Predictor
## 📌 Overview
This project aims to predict laptop prices based on various features such as brand, type, RAM, GPU, operating system, and memory configuration. It involves extensive data cleaning, feature engineering (especially memory storage extraction and classification), and the implementation of regression models within a pipeline.

## ⚙️ Tech Stack
Python 🐍

Pandas & NumPy for data handling

Scikit-learn for preprocessing and regression models

Jupyter Notebook for development and testing

Matplotlib / Seaborn for visualization

## 🧼 Data Cleaning and Feature Engineering
Converted memory sizes like 1TB+256GB into structured numeric columns.

Split memory into types: HDD, SSD, Hybrid, Flash Storage.

One-hot encoding applied to categorical variables like brand, type, OS, etc.

Dropped unnecessary or redundant columns.

## 📌 How to Run

## 📦 Model Export
Final trained model is saved as:
import pickle

pickle.dump(df,open('df.pkl','wb'))
pickle.dump(pipe,open('pipe.pkl','wb'))



