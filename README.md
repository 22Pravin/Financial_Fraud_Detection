# Fraud Detection Model

This repository contains a machine learning-based fraud detection model developed in Python using Logistic Regression. It identifies fraudulent transactions in credit card transaction datasets. The project includes exploratory data analysis (EDA), data preprocessing, model training, and a user-friendly interface for uploading new transaction data to predict their legitimacy.

## Features

- **Exploratory Data Analysis**: Visualization of class distribution, correlation heatmap, and transaction amount patterns.
- **Balanced Dataset**: Handles class imbalance using under-sampling.
- **Logistic Regression**: Builds a simple yet effective model for binary classification.
- **Evaluation Metrics**: Includes accuracy, confusion matrix, and classification report.
- **Interactive File Upload**: Allows users to upload transaction datasets for prediction.

## Dataset

The model uses a Kaggle dataset (`creditcard.csv`), which contains anonymized credit card transactions with labels indicating fraudulent (`Class = 1`) and legitimate (`Class = 0`) transactions.

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/fraud-detection-model.git
   cd fraud-detection-model
   ```

2. Install required Python libraries:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn ipywidgets
   ```

3. Ensure Jupyter Notebook or Jupyter Lab is installed.

---

## Usage

1. **Run the Notebook**:
   Open the `Fraud_Detection_Model.ipynb` file in Jupyter Notebook or Jupyter Lab and execute the cells sequentially.

2. **EDA and Preprocessing**:
   - Inspect missing values and class distributions.
   - Visualize transaction patterns and correlations.
   - Balance the dataset using under-sampling.

3. **Train the Model**:
   - The logistic regression model is trained on the balanced dataset.
   - Evaluate the model on training and testing data.

4. **Make Predictions**:
   - Use the provided upload interface to analyze a new CSV file of transactions.
   - The model predicts each transaction as either "Fraudulent" or "Legitimate."

---

## How It Works

1. **Data Preprocessing**:
   - The data is split into training and testing sets.
   - Class imbalance is addressed by under-sampling legitimate transactions.

2. **Model Training**:
   - A logistic regression model is trained to distinguish between fraudulent and legitimate transactions.
   - Metrics like accuracy and confusion matrix evaluate the model's performance.

3. **Interactive Prediction**:
   - Upload a transaction file using the widget.
   - The model predicts the legitimacy of each transaction and provides visual feedback.

---

## Example Output

### Class Distribution
A visualization showing the imbalance between legitimate and fraudulent transactions.

### Confusion Matrix
An annotated heatmap displaying the model's predictions against actual labels.

### Predictions on Uploaded File
- Tabular output indicating the legitimacy of each transaction.
- Bar chart summarizing the distribution of predictions.

---

## File Structure

- `Fraud_Detection_Model.ipynb`: Main notebook with the model, EDA, and file upload functionality.
- `creditcard.csv`: The dataset used for training and testing the model (you must download this dataset from [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)).

---

## Requirements

- Python 3.7+
- Jupyter Notebook
- Libraries: `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`, `ipywidgets`

---

## Future Enhancements

- Incorporate more sophisticated models like Random Forest or XGBoost.
- Address class imbalance using Synthetic Minority Oversampling Technique (SMOTE).
- Add support for real-time transaction streaming and prediction.
- Expand EDA with feature engineering for improved performance.

---

## License

This project is licensed under the MIT License.

---

Let me know if you’d like to make adjustments or add more details!
