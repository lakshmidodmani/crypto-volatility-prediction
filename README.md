# Crypto Volatility Prediction Project

## Project Overview
This project predicts cryptocurrency market volatility using machine learning techniques. 
The dataset contains historical crypto market data including price, volume, and market capitalization.

The goal of this project is to analyze cryptocurrency price behavior and build a machine learning model to predict volatility.

---

## Dataset
The dataset includes the following features:

- Open Price
- High Price
- Low Price
- Close Price
- Volume
- Market Cap
- Timestamp
- Crypto Name

---

## Project Structure

crypto-volatility-project

data → dataset.csv.zip

notebooks → eda_analysis.ipynb

src → train_model.py

models → volatility_model.pkl

reports → eda_report.pdf, HLD.pdf, LLD.pdf, final_report.pdf

requirements.txt → Python dependencies

README.md → Project documentation

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn

---

## Machine Learning Model

Random Forest Regressor is used to predict cryptocurrency volatility.

Steps:
1. Data preprocessing
2. Feature engineering
3. Model training
4. Model evaluation
5. Model saving

---

## Model Output

The trained model is saved as:

models/volatility_model.pkl

This model can be used for future volatility prediction.

---

## Conclusion

The project demonstrates how machine learning can be applied to financial time-series data to predict cryptocurrency volatility and analyze market behavior.  
