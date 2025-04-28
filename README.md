# Task 3: Linear Regression - Housing Price Prediction

## 📚 Objective
Implement and understand Simple & Multiple Linear Regression models using the Housing Price Prediction dataset.

---

## 🛠️ Tools Used
- Python
- Pandas
- Numpy
- Matplotlib
- Scikit-learn

---

## 📂 Dataset
- **Name**: Housing.csv
- **Features**: Area, Bedrooms, Bathrooms, Stories, Parking, Main Road Access, Guestroom, Basement, Hot Water Heating, Air Conditioning, Furnishing Status, Preferred Area
- **Target Variable**: Price

---

## 🔥 Steps Performed
1. **Data Loading**: Loaded Housing.csv dataset.
2. **Preprocessing**: Encoded categorical features using `pd.get_dummies`.
3. **Train-Test Split**: 80% training, 20% testing.
4. **Model Building**: Trained Linear Regression model using `sklearn.linear_model.LinearRegression`.
5. **Model Evaluation**:
    - Mean Absolute Error (MAE): ₹970,043.40
    - Mean Squared Error (MSE): 1,754,318,687,330.66
    - R² Score: 0.653
6. **Visualization**: Scatter plot for Area vs Price (Simple Regression view).

---

## 📊 Results Interpretation
- R² Score of 0.653 indicates a moderately strong model.
- Positive correlation between Area and Price is visible.
- Errors are acceptable given the large price scales.

---

## 📖 Interview Questions Answered
- Regression assumptions
- Coefficient interpretations
- R² significance
- MAE vs MSE
- Multicollinearity detection
- Simple vs Multiple Regression
- Why Linear Regression is unsuitable for classification
- Effects of violating assumptions

---

## 📦 How to Run
```bash
pip install pandas numpy matplotlib scikit-learn
jupyter notebook Task3_LinearRegression.ipynb
