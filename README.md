Heart Disease Prediction Using Machine Learning and Neural Networks

## Overview

A complete machine learning pipeline that predicts the presence of 
heart disease in patients using the Cleveland Heart Disease dataset 
from the UCI Machine Learning Repository. Three traditional ML models 
(Logistic Regression, Random Forest, SVM) are benchmarked against a 
custom Artificial Neural Network.


## Tech Stack

- Python 3.11.9
- pandas, NumPy
- scikit-learn (traditional ML)
- TensorFlow / Keras (ANN)
- matplotlib, seaborn (visualisations)

## How to Run

1. Clone the repo: `git clone <repo-url>`
2. Create a virtual environment: `python -m venv venv`
3. Activate it (Windows): `.\venv\Scripts\Activate.ps1`
4. Install dependencies: `pip install numpy pandas matplotlib seaborn scikit-learn tensorflow jupyter ipykernel`
5. Download the dataset from Kaggle (link below), place in `data/heart_cleveland.csv`
6. Open the notebooks in VS Code and run them in order

## Dataset Source

[Heart Disease Cleveland UCI](https://www.kaggle.com/datasets/cherngs/heart-disease-cleveland-uci) on Kaggle (297 rows, 14 columns).

## License

This project was submitted as coursework. Code is shared for educational and 
review purposes only.
