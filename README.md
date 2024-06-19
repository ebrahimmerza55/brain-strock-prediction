# brain-strock-prediction
brain-strock-prediction
### Graduation Project: Brain Stroke Prediction and Pipeline Development

### Insight Report: Brain Stroke Prediction and Pipeline Development

**Project Overview:**

The objective of this project was to develop a robust machine learning pipeline to predict the occurrence of brain strokes using a dataset comprising various health metrics of patients. The project involved several stages including data cleaning, exploratory data analysis (EDA), feature engineering, model building, and pipeline development.

**Key Findings and Insights:**

1. **Data Cleaning and Preprocessing:**
   - The dataset initially contained missing values and outliers which were addressed to ensure data quality.
   - Categorical variables were converted into numeric formats to facilitate model training.
   - Missing values in the `bmi` column were filled using the median value to minimize bias.

2. **Exploratory Data Analysis (EDA):**
   - The gender distribution showed a higher percentage of females compared to males, with a negligible percentage classified as 'Other'.
   - The majority of patients did not have a history of stroke, indicating an imbalanced dataset.
   - Visualization techniques like pie charts and bar graphs were used to understand the distribution of variables such as gender, heart disease, and marital status.
   - Correlation analysis revealed significant relationships between certain health metrics and stroke occurrence.

3. **Feature Engineering:**
   - Feature importance analysis using the Extra Trees Classifier highlighted key predictors for stroke occurrences, such as age, average glucose level, and BMI.
   - One-hot encoding was employed to handle categorical variables, enhancing the dataset's suitability for machine learning algorithms.

4. **Model Building and Evaluation:**
   - Several machine learning models were implemented, including Random Forest, Decision Tree, and Logistic Regression.
   - The Random Forest model demonstrated the highest accuracy, making it the preferred choice for the final pipeline.
   - Confusion matrices and accuracy scores were used to evaluate model performance, revealing that the Random Forest model had a train accuracy of approximately 99% and a test accuracy of around 95%.

5. **Handling Imbalanced Data:**
   - The dataset exhibited a significant class imbalance, with fewer instances of stroke occurrences.
   - Random OverSampling was applied to balance the dataset, which improved the model's ability to accurately predict stroke occurrences.

6. **Cross-Validation and Model Selection:**
   - Cross-validation techniques were used to ensure the model's reliability and generalizability.
   - Ensemble methods, such as voting classifiers, were explored to further enhance model performance.

7. **Pipeline Development:**
   - An end-to-end machine learning pipeline was developed to streamline the process of data preprocessing, feature selection, scaling, and model training.
   - The pipeline ensures scalability and reproducibility, making it suitable for deployment in real-world scenarios.

8. **Model Deployment:**
   - The trained Random Forest model was saved for future use in a real-time prediction system.
   - The deployment-ready model can be integrated into healthcare applications to assist in early stroke detection and prevention.

**Conclusion:**

The project successfully developed a machine learning pipeline capable of predicting brain stroke occurrences with high accuracy. Through meticulous data cleaning, feature engineering, and model evaluation, the final pipeline is robust and reliable. The insights gained from this project highlight the importance of various health metrics in predicting strokes and demonstrate the effectiveness of advanced machine learning techniques in healthcare analytics.

