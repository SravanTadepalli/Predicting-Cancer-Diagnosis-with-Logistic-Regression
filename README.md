# Predicting-Cancer-Diagnosis-with-Logistic-Regression

## Project Overview

This project aims to develop a Logistic Regression model to predict whether a tumor is malignant or benign based on given medical data. The goal is to assist in early cancer diagnosis, improving patient outcomes by enabling timely medical intervention.

## Dataset

The dataset contains medical records with tumor characteristics. The key features include:

- **Radius Mean** - Mean of distances from the center to points on the perimeter
- **Texture Mean** - Standard deviation of gray-scale values
- **Perimeter Mean** - Mean size of the tumor perimeter
- **Area Mean** - Mean size of the tumor area
- **Smoothness Mean** - Local variation in radius lengths
- **Compactness Mean** - Ratio of perimeter squared to area
- **Concavity Mean** - Severity of concave portions of the contour
- **Concave Points Mean** - Number of concave portions of the contour
- **Symmetry Mean** - Symmetry of the tumor shape
- **Fractal Dimension Mean** - Measurement of tumor complexity
- **Diagnosis** - Target variable (0 = Benign, 1 = Malignant)

## Project Workflow

1. **Data Preprocessing**
   - Load and clean the dataset
   - Handle missing values (if any)
   - Normalize/scale numerical features
2. **Exploratory Data Analysis (EDA)**
   - Visualize data distribution and relationships
   - Identify key features influencing the diagnosis
   - Check for class imbalances
3. **Feature Selection**
   - Choose the most relevant features for prediction
   - Perform correlation analysis
4. **Model Building**
   - Split the dataset into training and testing sets
   - Train a Logistic Regression model
   - Evaluate performance using accuracy, precision, recall, and F1-score
5. **Model Interpretation and Insights**
   - Analyze feature importance
   - Discuss implications for medical diagnosis

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib & Seaborn
- Scikit-learn
- Jupyter Notebook

## Results and Insights

- The model predicts whether a tumor is malignant or benign based on medical attributes.
- Key features influencing cancer diagnosis are identified.
- Performance metrics (accuracy, precision, recall, and F1-score) are used to evaluate the model’s effectiveness.

## Future Improvements

- Implement other classification models (e.g., Random Forest, SVM, Neural Networks) for comparison.
- Use feature engineering techniques to improve predictive accuracy.
- Deploy the model as a web application for easy access by medical professionals.

