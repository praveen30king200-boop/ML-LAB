# Machine Learning Lab

This repository contains the programs and experiments completed as part of the **Machine Learning Laboratory**.

The lab exercises demonstrate fundamental concepts of Machine Learning using Python, Jupyter Notebook, Pandas, Scikit-learn, Matplotlib, and Seaborn.

## 📂 Repository Contents

| File                               | Description                                                                         |
| ---------------------------------- | ----------------------------------------------------------------------------------- |
| `111_ML lab ex1-checkpoint.ipynb`  | Machine Learning experiment using the Iris dataset and Decision Tree classification |
| `111_ML lab ex.2-checkpoint.ipynb` | Additional Machine Learning laboratory experiment                                   |

## 🧪 Experiment 1 – Iris Classification

The first experiment works with the **Iris dataset**.

The notebook performs:

* Loading the Iris dataset
* Reading the dataset using Pandas
* Checking for missing values
* Performing statistical analysis using `describe()`
* Splitting the data into training and testing sets
* Training a Decision Tree Classifier
* Making predictions on test data
* Evaluating the model using a classification report
* Visualizing the Decision Tree
* Saving the generated tree visualization

The implementation uses Scikit-learn's `DecisionTreeClassifier`.

## 🛠️ Technologies Used

* **Python**
* **Jupyter Notebook**
* **Pandas**
* **Scikit-learn**
* **Matplotlib**
* **Seaborn**
* **Graphviz**
* **pydotplus**

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/praveen30king200-boop/ML-LAB.git
cd ML-LAB
```

Install the required Python libraries:

```bash
pip install pandas scikit-learn matplotlib seaborn jupyter pydotplus graphviz
```

Start Jupyter Notebook:

```bash
jupyter notebook
```

Then open the required `.ipynb` file and run the cells.

## 📊 Dataset

The experiments use the **Iris dataset**, a commonly used dataset for demonstrating classification algorithms.

The dataset contains measurements of:

* Sepal Length
* Sepal Width
* Petal Length
* Petal Width

The target variable represents the Iris flower variety.

## 🌳 Machine Learning Algorithm

### Decision Tree Classifier

A Decision Tree is a supervised machine learning algorithm used for classification and regression.

In this repository, the Decision Tree classifier is trained using the Iris dataset to predict the flower species from its measurements.

The notebook also generates a visual representation of the trained decision tree.

## 📈 Model Evaluation

The model performance is evaluated using a **classification report**, which provides metrics such as:

* Precision
* Recall
* F1-score
* Support

These metrics help determine how well the classifier predicts each Iris species.

## 🎯 Learning Objectives

The main objectives of this laboratory are to:

1. Understand the basic Machine Learning workflow.
2. Load and explore a dataset using Pandas.
3. Perform basic data preprocessing.
4. Divide data into training and testing sets.
5. Build a classification model using Scikit-learn.
6. Evaluate model performance.
7. Visualize a Decision Tree.
8. Gain practical experience with Python-based Machine Learning.

## 👨‍💻 Author

**Praveen**

GitHub: [praveen30king200-boop](https://github.com/praveen30king200-boop)

## 📄 License

This repository is intended for **educational and academic purposes** as part of Machine Learning Laboratory coursework.
