# Customer Churn Prediction with Mock Data

This project demonstrates a machine learning pipeline for predicting customer churn using mock data. The pipeline includes data preprocessing, model training, evaluation, and feature importance analysis. It uses Python's Scikit-learn library and a Random Forest classifier.

## Key Features
- **Mock Data Generation**: Simulated data including customer demographics, purchase history, and engagement metrics.
- **Data Preprocessing**: Categorical encoding, feature scaling, and train-test splitting.
- **Model Training**: Random Forest classifier for churn prediction.
- **Evaluation Metrics**: Accuracy, ROC-AUC, and a classification report.
- **Feature Importance**: Insights into the model's decision-making process.

## Technologies Used
- Python
  - NumPy
  - Pandas
  - Scikit-learn
- Random Forest Classification

## How to Use

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/customer-churn-prediction.git
```

### 2. Navigate to the Project Directory
```bash
cd customer-churn-prediction
```

### 3. Install Dependencies
Make sure you have Python 3.7+ installed and set up. Install the required libraries:
```bash
pip install -r requirements.txt
```

### 4. Run the Script
Execute the Python script to generate mock data, train the model, and evaluate the results:
```bash
python churn_model.py
```

## Results
After running the script, you will see:
- **Classification Metrics**: Accuracy, Precision, Recall, F1-score, and ROC-AUC.
- **Feature Importance**: Ranked features by importance in predicting churn.

## Project Structure
```
customer-churn-prediction/
├── churn_model.py        # Main script for data generation, training, and evaluation
├── requirements.txt      # List of dependencies
├── README.md             # Project description and usage guide
```

## Contributions
Contributions are welcome! Feel free to open issues, suggest features, or submit pull requests.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
