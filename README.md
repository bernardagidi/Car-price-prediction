# 🚗 Car Price Prediction

A Machine Learning project that predicts the selling price of a used car based on its features such as manufacturing year, fuel type, transmission, mileage, engine size, horsepower, and other relevant attributes.

<img width="131" height="123" alt="Image" src="https://github.com/user-attachments/assets/4fbe9d24-176e-4867-91fc-380624586894" />





## 📌 Project Overview

The goal of this project is to build a predictive model that estimates the market price of a used car. Accurate price prediction helps buyers and sellers make informed decisions.

The project follows the complete machine learning workflow:
- Data Collection
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Training
- Model Evaluation
- Price Prediction

---

## 📂 Project Structure

```
Car-Price-Prediction/
│
├── data/
│   ├── car_data.csv
│
├── notebooks/
│   ├── Car_Price_Prediction.ipynb
│
├── models/
│   ├── trained_model.pkl
│
├── app.py
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 📊 Dataset

The dataset contains information about used cars, including:

- Brand
- Model
- Year
- Fuel Type
- Transmission
- Mileage
- Engine Capacity
- Horsepower
- Number of Owners
- Selling Price

---

## 🛠 Technologies Used

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## ⚙️ Machine Learning Workflow

### 1. Data Preprocessing

- Removed missing values
- Handled categorical variables
- Feature encoding
- Feature scaling (if applicable)

### 2. Exploratory Data Analysis

- Correlation analysis
- Distribution plots
- Feature relationships
- Outlier detection

### 3. Model Training

Models tested include:

- Linear Regression
- Random Forest Regressor
- Decision Tree Regressor
- Gradient Boosting (if used)

The best-performing model was selected based on evaluation metrics.

---

## 📈 Evaluation Metrics

The model performance was evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/car-price-prediction.git
```

Navigate into the project directory

```bash
cd car-price-prediction
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
python app.py
```

---

## 💡 Example Prediction

Input:

- Year: 2018
- Fuel Type: Petrol
- Transmission: Manual
- Mileage: 55,000 km
- Engine: 1500 cc

Output:

```
Predicted Price: $12,450
```

---

## 📷 Sample Visualizations

- Price Distribution
- Correlation Heatmap
- Feature Importance
- Actual vs Predicted Prices

---

## 🎯 Future Improvements

- Hyperparameter tuning
- Deploy using Flask or Streamlit
- Add deep learning models
- Integrate live car market data
- Improve prediction accuracy with more features

---

## 👤 Author

**Your Name**

GitHub: https://github.com/yourusername

LinkedIn: https://linkedin.com/in/yourprofile

---

## 📄 License

This project is licensed under the MIT License.

---

## ⭐ Acknowledgements

- Scikit-learn Documentation
- Kaggle Dataset Contributors
I am open to collaborate on data analysis, statistical analysis and visualization
