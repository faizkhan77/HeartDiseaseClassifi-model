# Heart Disease Classification Project

Welcome to the Heart Disease Classification project repository! In this machine learning project, the heart disease dataset (`heart.csv`) from Kaggle is used for classification. The project involves loading the dataset, removing outliers, converting text columns to numbers using label encoding and one-hot encoding, applying scaling, building classification models (SVM, Logistic Regression, Random Forest), and evaluating model accuracy. Additionally, Principal Component Analysis (PCA) is applied to reduce dimensions and analyze its impact on model accuracy.

## Project Overview

### Dataset

- **Heart Disease Dataset:**
  - The dataset contains features related to heart health.
  - Downloaded from [Kaggle - Heart Failure Prediction](https://www.kaggle.com/fedesoriano/heart-failure-prediction).

### Data Preprocessing

- **Outlier Removal:**
  - Outliers are removed using Z score to enhance data quality.

- **Text to Number Conversion:**
  - Text columns are converted to numbers using label encoding and one-hot encoding.

- **Scaling:**
  - Features are scaled to ensure uniformity in the dataset.

### Model Building

- **Classification Models:**
  - Various classification models (SVM, Logistic Regression, Random Forest) are built to predict heart disease.
  - Model accuracy is evaluated using cross-validation scores.

### PCA for Dimensionality Reduction

- **Principal Component Analysis (PCA):**
  - PCA is applied to reduce the dimensions of the dataset.
  - The impact of PCA on model accuracy is analyzed.

## Project Execution

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/heart-disease-classification.git
   cd heart-disease-classification
   ```

2. **Download Dataset:**
   - Download the heart disease dataset (`heart.csv`) and place it in the `Exercise` folder.

3. **Run the Project:**
   - Execute the Jupyter Notebook (`heart_disease_classification.ipynb`) in your preferred environment.

4. **Follow Notebook Instructions:**
   - Run the notebook cells sequentially to load the data, preprocess it, build classification models, and analyze the impact of PCA on model accuracy.

## Note

This Heart Disease Classification project showcases the application of various classification models on a heart disease dataset. The removal of outliers, conversion of text columns, scaling, and dimensionality reduction using PCA are integral parts of the project. Analyze the trade-off between accuracy and computation while considering PCA for dimensionality reduction.

Feel free to explore, modify, and utilize this project for heart disease classification tasks. If you have any questions or suggestions, please create an issue in the repository.

Navigate through the intricacies of heart health with the Heart Disease Classification project! ❤️📈💻
