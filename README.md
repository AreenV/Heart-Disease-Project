# Heart Disease Prediction using Machine Learning

## About the Project

This project is about predicting whether a person is likely to have heart disease based on their medical information. I used Python and different machine learning algorithms to explore the dataset, train models and compare their performance.

The main aim was to see how accurately machine learning could classify patients based on factors like age, blood pressure, cholesterol, chest pain, maximum heart rate and other clinical parameters.

## What I Did

- Explored and analysed the heart disease dataset using Pandas, Matplotlib and Seaborn.
- Created visualisations to understand relationships between different medical attributes and heart disease.
- Split the data into training and testing sets.
- Implemented and compared three machine learning algorithms:
  - Logistic Regression
  - K-Nearest Neighbors (KNN)
  - Random Forest
- Used RandomizedSearchCV and GridSearchCV for hyperparameter tuning.
- Evaluated the models using accuracy, precision, recall, F1-score, confusion matrix and ROC curve.
- Used feature coefficients to understand which attributes had a greater influence on the predictions.
- Experimented with feature scaling, One-Hot Encoding and a Gradient Boosting Classifier.
- Saved the trained model using Joblib and tested it on new patient data.

## Results

After experimenting with different models and parameters, Logistic Regression gave the best performance on the Cleveland dataset, with an accuracy of approximately **88.5%**.

I also tested the model on data from other hospitals (Hungary, Switzerland and VA Long Beach). The accuracy dropped to around **74%**, mainly because the external datasets had a large number of missing values, especially in some of the more important features.

This was an interesting part of the project because it showed that a model performing well on one dataset does not necessarily mean it will perform equally well on completely different data.

## Tools Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

## Dataset

The project uses the Heart Disease dataset available on Kaggle, originally based on data from the UCI Machine Learning Repository.

Dataset: https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data

Two CSV files are used in the notebook:
- `heart-disease.csv`
- `heart_disease_uci.csv`

Make sure both files are available in the working directory before running the notebook.

## How to Run

1. Clone or download this repository.
2. Install the required libraries:

   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn joblib
   ```

3. Place the two dataset CSV files in the same directory as the notebook.
4. Open `Heart-Disease-Project.ipynb` in Jupyter Notebook.
5. Run the cells in order.

## Conclusion

This project helped me understand how machine learning can be applied to a real-world dataset. Apart from building and comparing models, I also got to work with data preprocessing, hyperparameter tuning, cross-validation and model evaluation.

One of the main things I learned was the importance of data quality and how missing values can affect a model's performance, especially when testing it on data from different sources.

**Note:** This project is for educational purposes and is not intended to be used as a medical diagnostic tool.
