Overview
This project aims to classify individuals' annual incomes based on various influential factors such as education level, age, gender, and occupation. The dataset contains labeled income categories (≤50K or >50K), providing a foundation for applying machine learning techniques to predict income classification.


Data Exploration: Utilize Pandas and visualization libraries to understand the dataset.
Data Cleaning: Handle missing values and duplicate entries, ensuring a clean dataset for analysis.
Feature Engineering: Create new features or modify existing ones to improve model performance.
Classification Models: Implement and compare various classification algorithms, including:
K-Nearest Neighbors (KNN)
Support Vector Machines (SVM)
Decision Tree Classifier
AdaBoost Classifier
Random Forest Classifier
XGBoost
Performance Evaluation: Assess the models using accuracy, precision, recall, and F1-score.
Installation
To run this project, you'll need to have Python installed along with the necessary libraries. You can install the required libraries using pip:


pip install pandas numpy matplotlib seaborn scikit-learn xgboost



Review the performance metrics to analyze the effectiveness of each classification model.

Data Cleaning and Preprocessing
Data Loading: Load the dataset using Pandas and check for duplicated and null values.
Duplicates and Nulls: Remove 21,162 duplicated rows and handle rows with '?' as NaN values.
Memory Optimization: Optimize memory usage by setting appropriate data types for each column.
Outlier Treatment: Address significant outliers in the 'capital gain' column.
Data Visualization: Use a heatmap to understand relationships between features.
Modeling
Implement classification algorithms and evaluate their performance using cross-validation.
The KNN model achieved 84% accuracy.
The SVM model is optimized to determine the best kernel.
The Decision Tree Classifier is evaluated for accuracy.
AdaBoost is applied to enhance the Decision Tree's performance, improving accuracy by 6%.
The Random Forest Classifier is also evaluated.
XGBoost is used as a final step, providing similar accuracy to AdaBoost but with better speed.
Results
Both XGBoost and AdaBoost achieved similar accuracy levels, but XGBoost proved to be the more efficient model for this dataset due to its faster execution time.

Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue for any improvements or suggestions.
