🏠 House Price Prediction using Machine Learning
📌 Project Overview
This project predicts house sale prices using Machine Learning techniques.
It automatically detects the problem type (Regression), compares multiple models, and selects the best-performing model based on evaluation metrics.
The objective is to build a data-driven system that provides accurate property price predictions and extracts business insights from the dataset.
📊 Dataset
The dataset contains various housing features such as:
Overall Quality
Living Area Size
Basement Area
Garage Capacity
Year Built
Lot Area
Number of Rooms
And more...
Target Variable:
SalePrice
⚙️ Technologies Used
Python
Pandas
NumPy
Scikit-learn
Matplotlib
🤖 Model Training & Evaluation
The system automatically:
Detects Regression problem
Trains multiple models
Compares performance metrics
Selects best model
Models Used
Linear Regression
Random Forest Regressor
📈 Model Performance
🔹 Linear Regression
MAE: 20,236
RMSE: 51,392
R² Score: 0.655
🔹 Random Forest Regressor (Best Model)
MAE: 17,543
RMSE: 28,636
R² Score: 0.893
The Random Forest model achieved the highest R² score (89.3%), making it the best-performing model.
🏆 Feature Importance (Top Factors)
Overall Quality
Ground Living Area
Total Basement Area
Second Floor Area
Basement Finished Area
Overall Quality is the strongest factor affecting house prices.
💡 Business Insights
Higher overall property quality significantly increases price.
Larger living areas strongly impact sale value.
Basement size contributes to higher pricing.
Garage capacity positively affects property value.
Newer properties generally sell at higher prices.
📂 Project Structure
Notebook file (.ipynb)
README.md
👨‍💻 Author
Shaikh Abubakar
