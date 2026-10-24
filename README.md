🏠 House Price Predictor

Predicts house prices using Linear Regression on the California Housing dataset. Built as part of my AI/ML learning journey.

🛠️ Tech Stack
Python
Pandas
NumPy
Scikit-learn
Matplotlib

📊 What This Project Does
Loads the California Housing dataset (20,640 rows, 8 features)
Splits data into 80% train and 20% test
Trains a Linear Regression model
Evaluates using MAE, MSE, RMSE and R2
Plots Actual vs Predicted prices
Predicts the price of a new house
📈 Results
Metric	Value
MAE	0.53
RMSE	0.75
R2 Score	0.58

Prices in this dataset are in units of $100,000, so an MAE of 0.53 means predictions are off by about $53,000 on average.

Actual vs Predicted

💡 Key Findings
Median income (MedInc) has a strong positive effect on price
Latitude and Longitude have negative coefficients, so location matters
Linear Regression explains about 58% of the price pattern
Next step: try Random Forest to improve R2

🚀 How to Run
pip install -r requirements.txt
jupyter notebook house_price_predictor.ipynb

📁 Project Files
house_price_predictor.ipynb : full notebook with code, outputs and charts
requirements.txt : libraries needed
actual_vs_predicted.png : result chart

👤 Author
Shanti | Aspiring AI/ML Developer | Open to Work
