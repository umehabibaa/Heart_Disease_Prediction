# Heart Disease Prediction
## Project Overview
This project predicts whether a person is at risk of heart disease using machine learning techniques. It leverages the famous Heart Disease UCI Dataset and applies exploratory data analysis (EDA), feature visualization, and multiple classification models to make predictions.

## Dataset
Source: Heart Disease UCI Dataset
The dataset contains various medical attributes such as:
- Age
- Sex
- Chest pain type
- Resting blood pressure
- Cholesterol
- Maximum heart rate achieved
- ST depression (oldpeak)
- Number of major vessels
- And more
- Target Variable: target
0 = No heart disease
1 = Heart disease present

## Tools & Libraries Used
Python

- pandas, numpy for data handling
- matplotlib, seaborn for data visualization
- scikit-learn for machine learning models & evaluation

## Exploratory Data Analysis (EDA)
- Checked for missing values
- Created pair plots to visualize feature relationships
- Plotted correlation heatmaps to highlight key predictive features

## Key Insights:
- Chest pain type (cp), maximum heart rate (thalach), and ST depression (oldpeak) show strong correlation with heart disease presence.
- These features are critical for building accurate models.

## Model Used
Logistic Regression

## Model Evaluation
Evaluation metrics include:
- Accuracy Score
- ROC Curve
- Confusion Matrix
- Feature Importance

## Results
The project demonstrates that simple yet effective models like Logistic Regression can predict heart disease risk with solid accuracy. Visualization of feature importance helps interpret the results in a medically relevant way.

## Conclusion
This project showcases:
- End-to-end machine learning workflow
- Medical data interpretation
- Feature importance analysis
- Performance evaluation using appropriate metrics

## Future Improvements
- Hyperparameter tuning
- Additional feature engineering
- Trying advanced models (e.g., Gradient Boosting, XGBoost)
- Deployment via a simple web interface

## Acknowledgements
Inspired by Zero to Mastery Machine Learning Course and the UCI Heart Disease dataset. 
Here's the link: https://zerotomastery.io/
