# Fitness & Lifestyle Prediction Model

## Overview
This AI/ML project focuses on predicting a person's fitness and lifestyle based on various health indicators such as sleep duration, physical activity level, stress level, and other health parameters. The model is trained on the `Sleep_health_and_lifestyle_dataset.csv` dataset and utilizes preprocessing techniques along with machine learning algorithms for prediction.

## Dataset
The dataset used in this project contains multiple features related to a person's health, including:
- **Age**
- **Gender**
- **Occupation**
- **Sleep Duration**
- **Quality of Sleep**
- **Physical Activity Level**
- **Stress Level**
- **Heart Rate**
- **Daily Steps**
- **Blood Pressure** (Systolic/Diastolic)
- **BMI Category**
- **Sleep Disorder**

## Data Preprocessing
1. **Handling Missing Values**: Checked for any missing data and handled appropriately.
2. **Feature Selection**: Dropped irrelevant features such as `Person ID`.
3. **Encoding Categorical Variables**:
   - Converted `Gender` into binary (Male = 0, Female = 1).
   - One-Hot Encoded categorical variables (`Occupation`, `BMI Category`, `Sleep Disorder`).
4. **Transforming Blood Pressure**:
   - Split `Blood Pressure` into `Systolic BP` and `Diastolic BP`.
5. **Feature Normalization**:
   - Standardized numerical features to improve model performance.
6. **Creating Target Variable**:
   - Defined `is_healthy` based on logical health classification criteria.

## Model Implementation
The project implements various machine learning models to predict a person's fitness level:
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- Neural Networks (Optional)
- 
## Results
After training and testing, the models are evaluated based on accuracy, precision, recall, and F1-score. The best-performing model is selected for final predictions.

## Conclusion
This project demonstrates the application of machine learning techniques in predicting fitness and lifestyle patterns. Further improvements can be made by using deep learning models and expanding the dataset with more diverse health parameters.

## Contributions
Feel free to contribute to this project by improving data preprocessing, experimenting with different models, or optimizing hyperparameters.

## License
This project is open-source and available under the [MIT License](LICENSE).

