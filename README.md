# Diabetes Dataset: Ensemble Classification Algorithms Comparison

## Project Structure

This project aims to compare the performance of three different ensemble classification algorithms - Random Forest, AdaBoost, and Gradient Boosting - on the diabetes dataset. The project comprises the following sections:

- **Data Loading and Visualization:** Load the "diabetes.csv" dataset using the `pandas` library and visualize the data's characteristics.
- **Data Preprocessing:** Split the data into features and target variables. Further divide the dataset into training and testing subsets.
- **Algorithm Implementation:** Implement RandomForest, AdaBoost, and Gradient Boosting classification algorithms using the `scikit-learn` library.
- **Hyperparameter Tuning:** Utilize GridSearchCV to find the best hyperparameter combinations for each algorithm.
- **Model Evaluation:** Train and evaluate the algorithms on the test dataset. Calculate accuracy scores and create confusion matrices for visual representation.
- **Results Comparison:** Compare the accuracy scores of the algorithms using a bar chart.

## Getting Started

1. Clone this repository to your local machine.
2. Install the required libraries using the following command:
3. Download the "diabetes.csv" dataset and place it in the project directory.
4. Run the code in the `diabetes_classification_comparison.py` file.

## Steps in the Code

1. Load and visualize the dataset using `pandas`, `matplotlib`, and `seaborn`.
2. Create a pie chart to display the class distribution.
3. Generate a correlation matrix heatmap to visualize feature correlations.
4. Split the data into features (X) and target (y) variables.
5. Split the dataset into training and testing sets using `train_test_split`.
6. Define RandomForest, AdaBoost, and Gradient Boosting classifiers.
7. Set up hyperparameter grids for GridSearchCV optimization.
8. Implement GridSearchCV to find the best hyperparameters for each algorithm.
9. Train the models using the best hyperparameters.
10. Calculate accuracy scores for each model on the test set.
11. Generate confusion matrices for each algorithm's predictions.
12. Visualize the confusion matrices using the `ConfusionMatrixDisplay` from `scikit-learn`.
13. Create a bar chart to compare the accuracy scores of the algorithms.

## Note

This project provides a hands-on comparison of ensemble classification algorithms' performance on the diabetes dataset. It demonstrates the ease and effectiveness of working with various classification algorithms using the `scikit-learn` library. Feel free to modify the code, experiment with different hyperparameters, and extend the analysis to other datasets.

Project owner: Pickardss
Project date: 01/08/2023
