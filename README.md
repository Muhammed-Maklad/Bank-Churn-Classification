# Bank Churn Classification

This project aims to predict customer churn for a bank based on various demographic, financial, and account activity features. Using advanced machine learning techniques, the solution provides insights into customer retention and supports proactive decision-making.

## Table of Contents
- [Overview](#overview)
- [Technologies Used](#technologies-used)
- [Data Preprocessing](#data-preprocessing)
- [Models and Evaluation](#models-and-evaluation)
- [Key Features](#key-features)
- [Usage](#usage)
- [Installation](#installation)
- [Contributing](#contributing)
- [License](#license)
- [Links](#links)

## Overview
Customer churn prediction is a crucial task for banks to identify customers who are likely to leave. This project builds and evaluates various machine learning models to predict churn based on customer behavior and account details.

### Key Goals:
- Accurately predict churn.
- Evaluate different machine learning models.
- Optimize model performance using hyperparameter tuning.
- Leverage advanced algorithms such as CatBoost and XGBoost for effective predictions.

---

## Technologies Used

### Programming Language:
- **Python**

### Libraries and Frameworks:
- **Data Manipulation**: Pandas, NumPy
- **Data Visualization**: Matplotlib, Seaborn
- **Machine Learning**:
  - **Scikit-learn**: Logistic Regression, Decision Tree, Random Forest, Gradient Boosting, AdaBoost, Extra Trees, SGD Classifier
  - **XGBoost**: Gradient Boosted Decision Trees
  - **CatBoost**: Gradient Boosting for categorical data
- **Pipeline Management**: Scikit-learn Pipelines, Custom Transformers
- **Hyperparameter Tuning**: RandomizedSearchCV

---

## Data Preprocessing

The project includes robust preprocessing steps:
- Handling missing values using custom imputation strategies (median, KNN, and mode).
- Encoding categorical features with OneHot, Ordinal, and Target encoders.
- Scaling numerical features with StandardScaler.
- Using a comprehensive pipeline (`FullPipeline1`) for streamlined preprocessing.

---

## Models and Evaluation

### Models Evaluated:
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boosting Classifier
- AdaBoost Classifier
- Extra Trees Classifier
- XGBoost Classifier
- CatBoost Classifier

### Final Model:
- **CatBoostClassifier**: Selected for its ability to handle categorical data effectively and its superior performance in terms of ROC-AUC score.

### Metrics:
- **Accuracy**
- **F1 Score**
- **ROC-AUC Score**

---

## Key Features

- **Automated Preprocessing**: Preprocessing pipeline for imputation, scaling, and encoding.
- **Custom Transformers**: Reusable transformers for feature engineering and handling categorical data.
- **Hyperparameter Tuning**: Optimized models using cross-validation and RandomizedSearchCV.
- **Model Evaluation**: Comprehensive evaluation using accuracy, ROC-AUC, and F1 score.

---

## Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/bank-churn-classification.git
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook or Python scripts to preprocess the data, train models, and evaluate performance.

---

## Installation

### Prerequisites:
- Python 3.8 or above
- Jupyter Notebook (optional)

### Setup:
1. Create a virtual environment:
   ```bash
   python -m venv venv
   ```
2. Activate the environment:
   - On Windows:
     ```bash
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```bash
     source venv/bin/activate
     ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## Contributing

Contributions are welcome! Follow these steps:
1. Fork the repository.
2. Create a new branch (`feature/your-feature`).
3. Commit your changes (`git commit -m 'Add a new feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a Pull Request.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Links

- **Application**: [Bank Churn Prediction App](https://bankchurnapp-ezg2aec7a0fdd0bu.westeurope-01.azurewebsites.net/predict)
- **Presentation**: [Project Presentation](https://www.canva.com/design/DAGYuDJzdJQ/TT3ertJc374JX62Tmsf07w/edit?utm_content=DAGYuDJzdJQ&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)
