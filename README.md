# best-selling-amazon-books
Machine learning project for analyzing best-selling books and predicting ratings using Python and Pandas.
# Amazon Best-Selling Books - Data Analysis & Rating Prediction

A Python-based data analysis and machine learning project exploring Amazon best-selling books and predicting book ratings using features such as price, publication year, reviews, and genre.

## 📌 Project Overview

This project analyzes a dataset of Amazon best-selling books to identify patterns in ratings, reviews, prices, genres, authors, and publication years.

The project also applies a machine learning model to predict book ratings based on selected book attributes.

## 📊 Dataset

The dataset contains **550 book records** with the following attributes:

* **Title** — Book title
* **Author** — Author name
* **User Rating** — Average user rating
* **Reviews** — Number of reviews
* **Price** — Book price
* **Year** — Publication year
* **Genre** — Fiction or Non Fiction

## 🔍 Analysis Performed

The project includes:

* Data inspection and descriptive statistics
* Duplicate removal and data cleaning
* Author popularity analysis
* Average rating comparison by genre
* Year-wise book distribution analysis
* Rating and price correlation analysis
* Top authors based on average rating
* Genre-wise price and rating analysis
* Premium book analysis based on price
* Statistical testing of rating differences
* Data visualization using Matplotlib

## 🤖 Machine Learning

A **Linear Regression** model is used to predict book ratings.

### Features

The model uses:

* Reviews
* Price
* Publication Year
* Encoded Genre

The `Title` and `Author` fields are excluded from the numerical prediction model.

### Workflow

```text
Data Loading
     ↓
Data Cleaning
     ↓
Exploratory Data Analysis
     ↓
Feature Preparation
     ↓
Genre Encoding
     ↓
Train-Test Split
     ↓
Linear Regression
     ↓
Model Evaluation
```

The dataset is divided into training and testing sets using an **80:20 split**.

Model performance is evaluated using **Mean Squared Error (MSE)** and **R² score**.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Google Colab / Jupyter Notebook

## 📁 Repository Structure

```text
best-selling-books-ml/
│
├── Amazon_Best_Selling_Books_Project.ipynb
├── bestsellers with categories.csv
└── README.md
```

## 📈 Key Findings

Some observations explored in the project include:

* Fiction and Non Fiction books show different average rating patterns.
* Book price and rating were analyzed for correlation.
* Author popularity was examined using the number of books appearing in the dataset.
* Ratings were compared across different genres and price categories.
* Statistical testing was used to examine differences in ratings.

## 🎯 Learning Outcomes

Through this project, I practiced:

* Data cleaning and preprocessing
* Exploratory data analysis
* Statistical analysis
* Data visualization
* Feature engineering
* Categorical variable encoding
* Train-test splitting
* Linear Regression
* Model evaluation using MSE and R²

## 👩‍💻 Author

**Pranjal Jain**

B.Tech — Artificial Intelligence & Machine Learning
