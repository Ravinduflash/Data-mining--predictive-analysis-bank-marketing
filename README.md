# Data-mining-predictive-analysis-bank-marketing

This repository contains a data mining project focused on predictive analysis using the **Bank Marketing Dataset**. The goal is to predict whether a client will subscribe to a **term deposit** based on various features such as age, job, marital status, education, and more.

## Project Overview

The **Bank Marketing Dataset** provides valuable insights into customer interactions with a bank’s marketing campaigns. It is highly relevant for **data scientists**, **financial analysts**, and **marketing professionals** looking to predict customer behavior and optimize marketing strategies. 

### Dataset

- **Source**: [Kaggle Bank Marketing Dataset](https://www.kaggle.com/discussions/accomplishments/510365)  
- **Features**:  
  - Includes age, job, marital status, education, default, balance, housing, loan, contact, day, month, duration, campaign, pdays, previous, poutcome.  
  - **Target Variable**: `y` (yes/no) indicating if the client subscribed to a term deposit.

---

## Problem Statement

The goal is to build a **predictive model** to classify whether a client will subscribe to a **term deposit**. This is a **binary classification** problem, with the target variable being `y` (yes or no).

---

## Project Structure

- **`data/`**: Contains the dataset files.
- **`notebooks/`**: Jupyter notebooks for data analysis and model building.
- **`models/`**: Saved models and their performance results.
- **`README.md`**: Project overview and documentation.

---

## Methodology

1. **Data Preprocessing**  
   - Handling missing values and outliers.  
   - Feature engineering and normalization for better model performance.  

2. **Exploratory Data Analysis (EDA)**  
   - Use of descriptive statistics and visualizations to understand data distribution and relationships between features.

3. **Model Building**  
   - Implemented **Logistic Regression** and **Random Forest** models.  
   - Applied **hyperparameter tuning** using Grid Search and cross-validation.  

4. **Model Evaluation**  
   - Models were evaluated using key metrics: **accuracy, precision, recall, and F1-score**.

---

## Results

- The **Random Forest model**, after optimization, achieved the highest performance with an **F1-score of 0.502**.
- This demonstrates the model’s effectiveness in predicting customer subscriptions.

---

## Insights and Recommendations

- **Targeted Marketing**: Focus on **middle-aged customers** who show higher subscription rates.
- **Personalized Offers**: Develop financial products tailored to **specific customer segments**.
- **Customer Retention**: Investigate non-subscribers to **enhance engagement strategies**.

---

## Getting Started

To run the project locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/bank-marketing-predictive-analysis.git
   cd bank-marketing-predictive-analysis
   ```

2. **Install dependencies**: Ensure you have all required Python packages by running:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run Jupyter notebooks** to explore the analysis and replicate the model training.

---

## Contributing

Contributions are welcome! Please submit a **Pull Request** with your improvements.

---

## Contact

For any questions or feedback, please reach out to:  
📧 [dulshanravindu505@gmail.com]

---

