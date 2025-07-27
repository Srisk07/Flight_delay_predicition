# light Delay Prediction Using Machine Learning

##  Overview
This project predicts flight delays using machine learning models based on historical flight and weather data. Delays in air travel cause significant economic and operational challenges — this solution aims to proactively predict such delays to improve scheduling, resource planning, and customer satisfaction.

## Project Structure

- `flight_delay_prediction_EDA.ipynb` – Exploratory Data Analysis (EDA) on flight and weather datasets.
- `flight_preprocessing.ipynb` – Data cleaning, encoding, and feature engineering.
- `weather_preprocessing.ipynb` – Processing and merging weather data with flight info.
- `merge_datasets.ipynb` – Combines datasets into one modeling-ready dataframe.
- `flight_delay_prediction_final.ipynb` – Final model building, training, evaluation, and predictions.
- `README.md` – Project documentation.

##  Key Features

- Data wrangling and preprocessing of multi-source datasets.
- EDA with visualizations to understand patterns in delays.
- Weather impact analysis on flight delays.
- Machine learning models like Random Forest, XGBoost, Logistic Regression.
- Accuracy and performance comparison of models.
- Notebook-based development for transparency and reproducibility.

##  Technologies Used

- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebooks
- Weather and flight delay datasets
- Git and GitHub for version control

##  Model Outcome

The final model predicts whether a flight is likely to be delayed based on departure/arrival time, carrier, origin, destination, and weather data. Performance metrics such as accuracy, F1-score, and confusion matrix are used for evaluation.

##  Future Work

- Add deep learning-based models (e.g., LSTM for time series prediction)
- Include real-time weather and flight API integration
- Deploy the model as a web application (e.g., using Flask or Streamlit)

## Author

Sri Harini  
 harinikumar215@gmail.com

---

 This project is part of my portfolio to showcase skills in machine learning, data preprocessing, EDA, and model evaluation.
