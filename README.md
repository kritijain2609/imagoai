Project Overview
This project focuses on processing hyperspectral imaging data to predict DON concentration in corn samples using machine learning. 
It includes data preprocessing, dimensionality reduction using PCA, model training with Random Forest, and evaluation using relevant metrics.

Installation Guide
Clone the Repository
To clone the repository, use the following command:
git clone https://github.com/kritijain2609/imagoai.git
cd imagoai

Install Dependencies
Ensure Python (version 3.8 or later) and pip are installed. Then, install the required dependencies using:
pip install -r requirements.txt


Repository Structure
imagoai/
│── TASK-ML-INTERN.csv
│── untitled1 (2).ipynb
│── README.md            

Results and Insights
Principal Component Analysis (PCA) was used for dimensionality reduction while preserving important variance.
A Random Forest Regressor was chosen for its efficiency in handling spectral reflectance data.
Model evaluation was conducted using Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R² Score.
