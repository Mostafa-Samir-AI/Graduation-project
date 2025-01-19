# Graduation Project Documentation

## Overview

- This repository contains the code and workflow for the graduation project. It is structured into three main Jupyter Notebooks that cover different stages of the project, from data exploration to final implementation. Below is an overview of each notebook and its purpose.

---

# Project Files

## 1. Data Exploration and Separation

File: `1.Data exploring and separation_cleaned.ipynb`

 **Purpose**

- Initial exploration of the dataset to understand its structure and characteristics.

- Separation of data into training and testing sets.

- Visualization of key features to gain insights.

**Key Steps**

1. Loading Data: Import and preview the dataset.

2. Data Analysis: Summary statistics and feature analysis.

3. Data Splitting: Separate the data into training and testing sets for modeling.

4. Visualization: Plot distributions and relationships between features.

---

## 2. Data Preprocessing and Modeling

File: `2.data preprocessing and modeling_cleaned.ipynb`

**Purpose**

- Prepare the data for machine learning.

- Build, train, and evaluate machine learning models.

**Key Steps**

1. Preprocessing:

	-  Handle missing values.

	- Encode categorical variables.

	-  Normalize or scale numerical features.

2. Modeling:

	- Train various machine learning models.

	- Perform hyperparameter tuning.

	- Evaluate models using metrics such as accuracy, precision, recall, etc.

---

## 3. Implementation in a Class

File: `3.putting it into class_cleaned.ipynb`

**Purpose**

- Encapsulate the project workflow into a Python class for better modularity and reusability.

- Provide a clean interface for running the entire pipeline.

**Key Steps**

1. Class Definition: Create a Python class to encapsulate data loading, preprocessing, and modeling steps.

2. Methods:

	- Data exploration.

	- Preprocessing and feature engineering.

	- Model training and evaluation.

3. Usage:

	- Demonstrate the class by running the full pipeline on sample data.

---

## Repository Structure

```
📂 Graduation Project
├── 1.Data exploring and separation_cleaned.ipynb
├── 2.data preprocessing and modeling_cleaned.ipynb
├── 3.putting it into class_cleaned.ipynb
├── README.md  # This documentation file
├── requirements: packages required to run the project
└── datasets.txt: link to download the data 
```


## How to Run

1. Clone the repository:

```bash
git clone git@github.com:Mostafa-Samir-AI/Graduation-project.git
cd graduation_project
```

2. Open the notebooks using Jupyter:

```bash
jupyter-notebook
```

3. Run the notebooks in the specified order.

---

## Requirements

```txt
Python 3.7+

Required libraries:

pandas

numpy

scikit-learn

matplotlib

seaborn

fuzzywazy

est
```

>[!NOTE]
>- I do not have the info about the exact version of libraries 
>- so its better to look for it on internet and download it manually

Install dependencies using:
```bash
pip install -r requirements.txt
```

---

Contact

For any inquiries or issues, please contact:

Author: Mostafa Samir

Email: mostafa.samir.ali.s@gmail.com

LinkedIn: https://linkedin.com/in/mostafa-samir-aa5325255