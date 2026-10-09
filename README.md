# iris-flower-classification

## Project Overview

This project uses machine learning to classify iris flowers into three species: Setosa, Versicolor, and Virginica based on their sepal and petal measurements.

## Objectives

* Explore and understand the Iris dataset.
* Perform exploratory data analysis (EDA).
* Visualize relationships between flower measurements.
* Train and evaluate multiple machine learning classification models.
* Compare model performance to identify the best-performing model.

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Dataset

The project uses the Iris dataset available through Scikit-learn. It contains 150 samples, four numerical features, and three flower species.

### Features

* Sepal length
* Sepal width
* Petal length
* Petal width

### Target Classes

* Setosa
* Versicolor
* Virginica

## Project Workflow

1. Load the Iris dataset.
2. Inspect the dataset structure and summary statistics.
3. Check for missing values.
4. Perform exploratory data analysis and visualization.
5. Split the data into training and testing sets using an 80:20 ratio.
6. Train and evaluate multiple classification models.
7. Compare model accuracy and observations.

## Machine Learning Models

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Decision Tree Classifier
* Random Forest Classifier

## Results

The K-Nearest Neighbors (KNN) model achieved **100% accuracy** on the test set in this experiment.

The visualizations showed that Setosa is clearly distinguishable, while Versicolor and Virginica have more overlapping feature distributions.

Note: The reported accuracy is based on this particular train-test split and does not guarantee the same performance on unseen data.

## How to Run

1. Clone or download this repository.
2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```
3. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```
4. Open the Iris classification notebook and run the cells.

## Project Structure

```text
iris-flower-classification/
├── README.md
└── iris_classification.ipynb
```

Note: Replace `iris_classification.ipynb` in this example with your actual notebook filename if it differs.

## Key Learnings

* Understanding the machine learning workflow.
* Performing exploratory data analysis.
* Visualizing numerical features.
* Training and evaluating classification algorithms.
* Comparing model performance using accuracy.

## Author

Data Science Project Portfolio
