🌾 Crop Production Prediction (CPP)
📌 Overview
This Streamlit-based web app predicts crop production based on historical agricultural data. It leverages machine learning models to estimate production based on area harvested and crop yield, providing valuable insights for farmers, policymakers, and analysts.

📂 Project Structure
CPP.py → Main application script
FAOSTAT_data.xlsx → Dataset containing agricultural data
trained_models.pkl → Serialized machine learning models
requirements.txt → Dependencies for running the app
🚀 Features
✅ Data Cleaning & Processing

Removes unnecessary columns
Handles missing values and outliers
Creates additional features for better predictions
✅ Machine Learning Models

Linear Regression
Random Forest Regressor
XGBoost Regressor
Compares model performance using R² Score
✅ Exploratory Data Analysis (EDA)

Distribution of crop production
Relationship between yield, area harvested, and production
Correlation heatmaps
✅ User-Friendly Web Interface

Predicts crop production using trained models
Allows users to input area harvested and yield
Displays model performance metrics
🛠️ Installation & Usage
1️⃣ Install Dependencies
Run the following command to install the required libraries:

bash
Copy
Edit
pip install -r requirements.txt
2️⃣ Run the Streamlit App
bash
Copy
Edit
streamlit run CPP.py
📊 How It Works
1️⃣ Loads & Cleans Data → Extracts useful features, removes outliers
2️⃣ Trains Models → Trains and evaluates machine learning models
3️⃣ User Input → Accepts area harvested and yield for prediction
4️⃣ Predicts Crop Production → Uses the selected model to generate predictions
5️⃣ Visualizes Data → Provides EDA insights through plots and heatmaps

🔗 Dependencies
Python 3.x
Streamlit
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn
XGBoost
