# Fraud_Detection
# Fraud Detection Using Machine Learning

This project is an end-to-end machine learning workflow for detecting fraudulent financial transactions. It involves data preprocessing, visualization, and predictive modeling using supervised learning techniques.

## 📊 Dataset

The dataset (`AIML Dataset.csv`) consists of simulated transaction records, including:
- `amount`
- `type` of transaction
- Flags such as `isFraud` and `isFlaggedFraud`

## 🔧 Key Steps

1. **Data Cleaning & Exploration**
   - Checked for null values and duplicates.
   - Analyzed the distribution of transaction types and fraud cases.

2. **Feature Engineering**
   - Applied Label Encoding to categorical variables.
   - Investigated relationships between transaction amount and fraud occurrence.

3. **Visualization**
   - Used scatter plots and histograms to visualize fraud trends.
   - Compared fraudulent vs non-fraudulent transactions based on amount and type.

4. **Machine Learning**
   - Built classification models to predict fraudulent transactions.
   - Evaluated model performance using metrics like accuracy and confusion matrix.

## 🧰 Technologies Used

- Python
- Pandas & NumPy
- Seaborn & Matplotlib
- Scikit-learn

## 📁 Project Structure

- `Fraud.ipynb`: Jupyter notebook containing the full project workflow.

## 🚀 Future Improvements

- Implement additional ML algorithms (e.g., Random Forest, XGBoost)
- Improve model evaluation with precision/recall analysis
- Hyperparameter tuning for better performance

## 📌 Conclusion

This project demonstrates how machine learning can be applied to detect anomalies in financial datasets and assist in fraud prevention.
