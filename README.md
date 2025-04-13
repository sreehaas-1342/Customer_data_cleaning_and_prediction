# Customer Transactions Data Preprocessing & Analysis

This project cleans and analyzes customer transaction data using Python (Google Colab).
This project predicts the purchase frequency of the user using he/she's age, spending score and annual income. 
## 🧪 Dataset
- Input: `unclean_customer_data.csv` (uploaded manually)
- Output: `cleaned_customer_data.csv` (after cleaning)

## 📊 Visualizations
- ![Income Distribution]
- ![image](https://github.com/user-attachments/assets/e191bc68-3054-4449-ae1d-df5209c2abd0)
- ![Income vs Spending]
- ![image](https://github.com/user-attachments/assets/669e7604-d902-46b8-8ced-87c8da3c8150)
These helped us understand customer spending behavior better.
## 🤖Machine Learning model
We built a Decision Tree Regressor to predict a customer’s Purchase_Frequency using:

Age

Annual Income

Spending Score

Used: from sklearn.tree import DecisionTreeRegressor

Model Testing:

Split the data: 80% train, 20% test

Tested prediction accuracy: how close predictions are to actual values. 

Added a feature to accept user input (Age, Income, Spending Score) and predict their buying frequency!

* Why This Project Matters:

In the real world, companies use customer profiling to:

Target marketing campaigns

Predict high-value customers

Optimize spending strategies

This project simulates that—cleaning real data, visualizing it, and using ML to make decisions.

## 📒 Notebook
- Full Colab code: [`customer_data_cleaning.ipynb`]

## 🧼 Data Cleaning Includes:
- Removing missing values
- Dropping duplicates
- Handling outliers
- Normalizing spending score

## 📦 Libraries Used
- pandas, numpy, seaborn, matplotlib, sklearn

---
🛠️ Tools & Libraries Used:

Google Colab (Python)

Pandas, NumPy (data handling)

Matplotlib, Seaborn (data visualization)

Scikit-learn (ML model)

📁 Outputs:

✅ The cleaned dataset cleaned_customer_data.csv

✅ The complete notebook c_data_cleaning.ipynb

✅ All plots and graphs (inside the notebook)



[![Open In Colab]: [https://colab.research.google.com/drive/1aTmPrwWv35bexIjJ5H0pVnzcniXgzdyu?usp=sharing](https://github.com/sreehaas-1342/Customer_data_cleaning_and_prediction.git)
Made by Sreehaas
