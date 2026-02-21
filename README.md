# CCMACLRL-Introduction-To-Machine-Learning-Activities

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-150458?logo=pandas&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit_Learn-Machine_Learning-F7931E?logo=scikit-learn&logoColor=white)
![NLP](https://img.shields.io/badge/NLP-Text_Processing-8E44AD?logo=grammarly&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-success)

This repository compiles all activities and projects completed in my **CCMACLRL: Introduction to Machine Learning** course. It serves as a structured collection of programming exercises and applications, showcasing the progression from foundational regression to advanced Natural Language Processing.

## Academic Context
* **Subject:** CCMACLRL - Introduction to Machine Learning
* **Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn, Google Colab

---

### ⋆‧°𓏲ּ𝄢 Activity 1: Regression Foundations
**Folder:** `Activity_01_LinearRegression`

Introduction to supervised learning using the Scikit-learn diabetes dataset to predict continuous numeric outcomes.

| Notebook | Description | Open in Colab |
| :--- | :--- | :--- |
| **Linear Regression** | Implementing predictive modeling for clinical variables and visualizing the relationship between features and target values. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/alhtb/CCMACLRL-Introduction-To-Machine-Learning/blob/main/Activity_01_LinearRegression/LinearRegression.ipynb) |

---

### ⋆‧°𓏲ּ𝄢 Activity 2: Classification & Normalization
**Folder:** `Activity_02_Classification`

Focuses on categorical prediction and the importance of feature scaling in distance-based algorithms.

| Notebook | Description | Open in Colab |
| :--- | :--- | :--- |
| **Supervised ML** | Multi-class classification of Iris species using **K-Nearest Neighbors (KNN)** and performance evaluation via Confusion Matrices. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/alhtb/CCMACLRL-Introduction-To-Machine-Learning-Activities/blob/main/Activity_02_Classification/SupervisedML(Classification).ipynb) |

---

### ⋆‧°𓏲ּ𝄢 Activity 3: Exploratory Data Analysis (EDA)
**Folder:** `Activity_03_EDA`

Understanding the dataset before modeling through statistical analysis and visualization. **Note: Requires `boston_house_prices.csv`**.

| Notebook | Description | Open in Colab |
| :--- | :--- | :--- |
| **Data Exploration** | Analyzing the Boston House Prices dataset. Includes missing value detection, descriptive statistics, and correlation heatmaps. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/alhtb//CCMACLRL-Introduction-To-Machine-Learning-Activities/blob/main/Activity_03_EDA/ExploratoryDataAnalysis.ipynb) |

---

### ⋆‧°𓏲ּ𝄢 Activity 4: Generalization & Regularization
**Folder:** `Activity_04_Overfitting`

A deep dive into the Bias-Variance tradeoff and techniques to prevent model overfitting.

| Notebook | Description | Open in Colab |
| :--- | :--- | :--- |
| **Overfitting Study** | Visualizing learning curves and applying regularization to ensure models generalize well to unseen data. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/alhtb//CCMACLRL-Introduction-To-Machine-Learning-Activities/blob/main/Activity_04_Overfitting/Underfitting,Generalization,AndOverfittingWithRegularizations.ipynb) |

---

### ⋆‧°𓏲ּ𝄢 Activity 5: Natural Language Processing
**Folder:** `Activity_05_NLP`

Applying machine learning to unstructured text data for automated classification tasks. **Note: Requires `spam.csv`**.

| Notebook | Description | Open in Colab |
| :--- | :--- | :--- |
| **NLP Classification** | Building a Spam Filter using **TF-IDF Vectorization** and comparing **Logistic Regression** vs. **SVM**. | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/alhtb//CCMACLRL-Introduction-To-Machine-Learning-Activities/blob/main/Activity_05_NLP/NLPandClassification.ipynb) |

---

## How to View or Run

### ⋆‧°𓏲ּ𝄢 To View Code & Outputs 
Simply click on the `.ipynb` files in the list above. GitHub renders the notebooks directly in the browser so you can review the logic and results without downloading anything.

### ⋆‧°𓏲ּ𝄢 To Run the Code
1. Click the "Open in Colab" badge next to the notebook.
2. **Important:** Certain activities require external datasets.
   - For **Activity 3**, ensure `boston_house_prices.csv` is uploaded.
   - For **Activity 5**, ensure `spam.csv` is uploaded.
3. Open the **Files** sidebar in Colab (folder icon on the left) and upload the required `.csv` file from the corresponding activity folder before running the cells.
