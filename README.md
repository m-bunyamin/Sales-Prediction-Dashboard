# Sales Prediction System

## 📌 Project Overview
- This project presents a data-driven sales forecasting system that integrates Data Warehousing, Machine Learning, and Business Intelligence to analyze and predict weekly sales.

- The system processes raw transactional data, transforms it into a structured warehouse format, and applies machine learning models to generate accurate sales predictions. An interactive dashboard is developed using Streamlit to visualize trends and model performance.


## 🛠️ Technologies Used
- Python
- Pandas
- Scikit-learn
- Streamlit
- Matplotlib
- Visual Studio Code

## 📂 Project Structure
- data_cleaning.py → Cleans raw data
- data_warehouse.py → Structures the data
- model_training.py → Trains ML model
- dashboard.py → Streamlit dashboard
- requirements.txt → Dependencies

## Machine Learning Model
The following model were implemented:
- Linear Regression
- Random Forest Regressor
- XGBoost Regressor

## Evaluation Metrics
Mean Absolute Error(MAE)
Root Mean Squared Error(RSME)
R² Score

## Model Performance
Linear Regression R² Score: 0.9819 
Random Forest R² Score: 0.2321 
XGBoost R² Score: 0.1733

# Best Model: 
Linear Regression because it achieved high accuracy due to strong linear relationships in engineered features.


# ▶️ How to Run the Project

## 1. Clone the repository
git clone https://github.com/m-bunyamin/Sales-Prediction-Dashboard.git
cd Sales-Prediction-Dashboard

## 2. Install dependencies
pip install -r requirements.txt

## 3. Run the dashboard
streamlit run dashboard.py

## Key Insights
- Data warehouse design significantly improves model performance
- Feature engineering plays a critical role in prediction accuracy
- Linear models can outperform complex models when relationships are linear
- Dashboard visualization enhances decision-making

## Limitations
- Dataset size may limit generalization
- Weekly sales can be highy volatile
- Current system evaluates predictions on historical sales data only

## Future Improvements
- Implement real-time future sales forecasting
- Add more advanced time-series models (ARIMA, LSTM)
- Integrate External features like holidays and promotion
- Explore large datasets

##  Features
- Data cleaning and preprocessing
- Machine learning prediction
- Interactive dashboard visualization



