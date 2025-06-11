# Molecular_Solubility_Predictor

## Overview: 
Built a machine learning model to predict the aqueous solubility (logS) of molecules — a critical property in the early stages of drug discovery. This project leverages regression algorithms to estimate how easily a compound can dissolve, aiding researchers in screening viable drug candidates with better pharmacokinetic properties.

## 🧰 Tech Stack: 
Python – Primary language for data handling and modeling

Pandas & NumPy – For efficient data cleaning and feature manipulation

Scikit-learn – Applied Linear Regression and Random Forest Regressor

Matplotlib & Seaborn – For data visualization and result interpretation

Jupyter Notebook / Google Colab – For interactive experimentation and visualization

## 🧩 System Architecture 
1. Data Loading → 2. Feature Engineering → 3. Model Training → 4. Evaluation & Visualization

Data Loading: Molecular descriptors and solubility labels are loaded into a structured DataFrame from a preprocessed dataset.

Feature Engineering: Checked for missing values, performed exploratory data analysis (EDA), and selected relevant features affecting solubility.

Model Training: Employed a train-test split strategy with two models: Linear Regression for baseline performance and Random Forest for non-linear learning.

Evaluation & Visualization: Measured accuracy using Mean Squared Error (MSE) and R² Score. Visualized predicted vs actual values and feature importance.

## Results and Evaluation Metric Graph 
![image](https://github.com/user-attachments/assets/0b97b90c-9805-486a-949e-1c10c7b41574)
