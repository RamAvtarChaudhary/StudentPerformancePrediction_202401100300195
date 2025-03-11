# StudentPerformancePrediction_202401100300195
Overview:-

This project aims to predict student performance using machine learning techniques. By analyzing factors like study time, past grades, and absences, we build a predictive model using a Decision Tree Classifier to determine whether a student is likely to perform well or poorly.

Technologies Used:-

Python
Pandas for data handling
Scikit-learn for machine learning
Decision Tree Classifier for classification

Dataset:-

The dataset consists of key attributes influencing student performance:

Study Time: Hours spent studying per day
Past Grades: Previous academic performance
Absences: Number of missed classes

Methodology:-

Data Collection: Gather relevant features affecting student performance.
Data Preprocessing: Extract and clean data for training/testing.
Model Selection: Use a Decision Tree Classifier for classification.
Model Training: Train the classifier using labeled data.
Prediction & Evaluation: Predict student performance and measure accuracy.

Output:-

The model predicts student performance (Good/Bad) and provides accuracy based on test data.
Sample Data:
   study_time  past_grades  absences  performance
0          2          70        3            1
1          3          80        1            1
...

Accuracy: 85.00%

Predictions:
   Actual  Predicted
0       1          1
1       0          0
...
