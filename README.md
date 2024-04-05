# OVERVIEW

Autism Spectrum Disorder (ASD) is a neurodevelopmental condition characterized by social communication difficulties and repetitive behaviors. Machine learning algorithms offer promising avenues for enhancing ASD diagnosis and understanding its underlying patterns through analysis of behavioral and clinical data.

## PROJECT COMPONENTS

1. Data Collection: Gathering relevant data, including behavioral observations, clinical assessments, and demographic information, from individuals diagnosed with ASD and typically developing individuals.

2. Data Preprocessing: Cleaning the data to remove noise, handling missing values, and standardizing the features to ensure consistency and improve model performance.

3. Model Selection: Machine learning algorithms for training, such as Support Vector Machines (SVM), Logistic Regression, based on the nature of the data and the desired outcomes.

4. Model Training: Training the selected model on the preprocessed data using appropriate training techniques, such as cross-validation or bootstrapping, to optimize performance and prevent overfitting.

5. Model Evaluation: Assessing the trained model's performance using evaluation metrics such as accuracy, precision, recall, F1-score, and receiver operating characteristic (ROC) curve analysis.

6. Model Tuning: Fine-tuning the model hyperparameters and adjusting the feature set to improve performance further, based on evaluation results and domain expertise.

7. Validation: Validating the trained model on independent datasets or through clinical validation studies to assess real-world applicability and generalizability.
   
##  DATASET

The project utilizes the Kaggle  dataset, a widely used benchmark dataset for autism disorder classification tasks. The dataset consists of 704 instances along with 21 unique constraints of autism disorder adult.

## LIBRARIES

Pandas – This library helps to load the data frame in a 2D array format and has multiple functions to perform analysis tasks in one go.

Numpy – Numpy arrays are very fast and can perform large computations in a very short time.


Matplotlib/Seaborn – This library is used to draw visualizations.

Sklearn – This module contains multiple libraries having pre-implemented functions to perform tasks from data preprocessing to model development and evaluation.

XGBoost – This contains the eXtreme Gradient Boosting machine learning algorithm which is one of the algorithms which helps us to achieve high accuracy on predictions.

Imblearn – This module contains a function that can be used for handling problems related to data imbalance.

