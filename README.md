# Predicting Restaurant Success in Sydney Using Zomato Dataset

## Overview

This project utilizes a real-world dataset containing over 10,000 records of restaurants in the Sydney area (2018). The dataset includes detailed information ranging from basic attributes such as restaurant names, addresses, and locations to advanced metrics like ratings and customer reviews. 

The aim is to use **feature engineering**, **predictive modeling**, and **deployment** to analyze and predict the success of restaurants. This project draws on data science skills including exploratory data analysis (EDA), building machine learning models, and deploying results to a public repository.

---

## Objectives

1. Analyze the Sydney restaurant dataset and extract meaningful insights.
2. Use feature engineering to create useful predictive features.
3. Build predictive models to determine the likelihood of a restaurant’s success.
4. Deploy the findings, code, and visualizations in a public repository.

---

## Dataset Description

### Key Details:
- **Source**: Zomato dataset containing information about restaurants in Sydney in 2018.
- **Records**: 10,000+ rows
- **Features**: 
  - Basic details: Restaurant name, address, location.
  - Advanced details: Cost for two, cuisines, ratings, and more.

### Feature Summary:
| **Feature Name**      | **Description**                                         |
|------------------------|---------------------------------------------------------|
| `Restaurant Name`      | Name of the restaurant.                                |
| `Address`              | Full address of the restaurant.                       |
| `Location`             | Suburb or area where the restaurant is located.       |
| `Cuisines`             | Type(s) of cuisines offered by the restaurant.        |
| `Average Cost for Two` | Estimated cost for two people dining.                 |
| `Rating`               | Restaurant rating (scale of 1–5).                     |
| `Number of Votes`      | Number of customer reviews received.                  |

---

## Project Workflow

### 1. **Data Preprocessing**
   - Handle missing values and clean the dataset.
   - Convert categorical variables (e.g., cuisines, location) to usable formats.
   - Normalize numerical features such as `Average Cost for Two` and `Number of Votes`.

### 2. **Exploratory Data Analysis (EDA)**
   - Visualize trends in ratings, costs, locations, and cuisines.
   - Understand correlations between features (e.g., rating and votes).

### 3. **Feature Engineering**
   - Extract key features like cuisine popularity, price ranges, and area-wise restaurant density.
   - Perform dimensionality reduction using **Principal Component Analysis (PCA)** to reduce feature redundancy.

### 4. **Predictive Modeling**
   - Build and evaluate models for predicting restaurant success using:
     - **Logistic Regression**
     - **Linear Regression**
     - **Gradient Descent**
     - Other suitable machine learning algorithms.
   - Use metrics like **accuracy**, **precision**, **recall**, and **F1 score** to evaluate models.

### 5. **Deployment**
   - Deploy code, analysis, and findings on a public GitHub repository.
   - Use visualizations to support conclusions.

---

## Installation and Setup

### Prerequisites:
- Python 3.8+
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `xgboost`, `flask` (if deploying locally).

### Steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/vibhores19/Zomato-Data-Sydney.git
   cd Zomato-Data-Sydney
