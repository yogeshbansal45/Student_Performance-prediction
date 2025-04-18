# Student_Performance_prediction

This project aims to predict student performance (Pass/Fail) based on various features using machine learning. The dataset is used to train a model that classifies students' performance based on their grades and other related factors.

## Features

- Predict whether a student will pass or fail based on input features.
- The target variable is binary: Pass (1) or Fail (0).
- Uses a Random Forest Classifier for prediction.

## Dataset

The dataset used for this project contains various student-related information, such as their grades, student ID, and other academic features. The target variable is "GradeClass," where students with grades <= 2 are considered to pass (1), and others are considered to fail (0).

## Installation

To run this project locally, you'll need to install the following dependencies:

```bash
pip install pandas scikit-learn seaborn matplotlib

Code Explanation
Data Preprocessing: The dataset is cleaned by dropping unnecessary columns such as StudentID and GradeClass. A new column Pass is created based on the GradeClass to mark students as pass (1) or fail (0).

Model Training: A Random Forest Classifier is used to train the model on the training dataset.

Evaluation: The model's performance is evaluated using a confusion matrix, classification report, and accuracy score.

Visualization: A heatmap of the confusion matrix is plotted using Seaborn and Matplotlib for better understanding.

Evaluation Metrics
Confusion Matrix: Shows the true positives, true negatives, false positives, and false negatives.

Classification Report: Provides precision, recall, f1-score, and support.

Accuracy Score: Overall accuracy of the model.

Contributing
If you'd like to contribute to this project, feel free to fork the repository and submit a pull request. Please ensure that your contributions adhere to the following guidelines:

Add clear and concise comments to your code.

Update the README if necessary.

License
This project is licensed under the MIT License.

Acknowledgments
Thanks to scikit-learn for providing the Random Forest Classifier.

Thanks to Seaborn and Matplotlib for creating great visualization tools.

