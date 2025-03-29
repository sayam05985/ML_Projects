# ML_Projects
# Titanic Survival Prediction

## Overview
This project leverages machine learning to predict passenger survival on the Titanic. It includes data preprocessing, exploratory data analysis (EDA), model training using a Random Forest classifier, and model evaluation.

## Problem Statement
The Titanic disaster raised critical questions about the factors that influenced passenger survival. This project analyzes key factors such as age, gender, and ticket class to predict survival probabilities using machine learning.

## Objectives
- **Data Preprocessing & Cleaning:** Handle missing values and prepare data for analysis.
- **Exploratory Data Analysis (EDA):** Identify survival patterns based on key factors.
- **Model Development & Training:** Train and fine-tune a Random Forest classifier.
- **Performance Evaluation & Insights:** Assess model accuracy and extract meaningful insights.

## Dataset
- **Source:** Titanic dataset from Seaborn.
- **Preprocessing Steps:**
  - Imputation of missing values for age, fare, and embarked columns.
  - Categorical encoding of non-numeric variables.
  - Feature scaling for numerical features.

## Methodology
1. **Data Preprocessing:**
   - Handle missing values.
   - Convert categorical variables into numerical format.
   - Normalize numerical features for better model performance.
2. **Model Training:**
   - Train a Random Forest classifier to predict survival.
3. **Model Evaluation:**
   - Evaluate performance using accuracy, confusion matrix, and classification report.

## Model Performance
- **Model Used:** Random Forest Classifier
- **Accuracy Achieved:** ~85%
- **Evaluation Metrics:**
  - Confusion Matrix
  - Classification Report (Precision, Recall, F1-score)

## Future Scope
- Improve feature engineering using domain-specific insights.
- Explore advanced ML models like XGBoost for better performance.
- Integrate deep learning techniques for enhanced accuracy.

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Titanic-Survival-Prediction.git
   cd Titanic-Survival-Prediction
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## Repository Structure
```
Titanic-Survival-Prediction/
│── data/
│   ├── titanic.csv
│── notebooks/
│   ├── Project_Titanic1.ipynb
│── src/
│   ├── preprocessing.py  # (Optional: Data processing scripts)
│   ├── model_training.py  # (Optional: Model training script)
│── images/  # (For screenshots or visualizations)
│── README.md
│── requirements.txt
│── edunet_titanic_project.pptx
│── .gitignore
```

## Contributing
Feel free to open issues or submit pull requests to improve this project!

## License
This project is open-source and available under the [MIT License](LICENSE).
