🍷 Wine Reviews - Quality Prediction Using Linear Regression

This project explores and analyzes the Wine Reviews dataset from Kaggle to predict wine quality scores (points) using machine learning. The goal is to build a Linear Regression model that estimates wine ratings based on attributes like price, country, variety, and other structured metadata.

<br>
📂 Dataset Overview

Source: Wine Reviews by zackthoutt on Kaggle

Size: 130,000+ wine reviews

File Types: CSV, JSON

Key Columns:

country: Country of origin

province: Region within the country

variety: Type of grape used

winery: Wine producer

points: Wine rating (target variable)

price: Price of the wine

description: Text review (not used in this model)

<br>
🛠️ Technologies Used

Python 3

Pandas – data cleaning and manipulation

Matplotlib – data visualization

Scikit-learn – model building and evaluation

<br>
🔍 Project Workflow
1. Data Cleaning & Preprocessing

Removed or filled missing values in critical columns (price, points, etc.)

Converted categorical variables (country, variety, province) using encoding

Filtered and selected features relevant to predicting wine ratings

2. Exploratory Data Analysis (EDA)

Visualized price distributions and correlations with ratings

Identified top wine varieties and their average scores

Analyzed feature relationships and variance

3. Model Building

Implemented Linear Regression using Scikit-learn

Split data into training and testing sets

Trained model on structured features

4. Model Evaluation

Used R² Score and Mean Squared Error (MSE) to evaluate model performance

Compared actual vs predicted scores to check accuracy

<br>
📈 Results & Insights

Linear Regression provided a basic yet interpretable model for score prediction.

Features like price, variety, and country showed meaningful influence on wine ratings.

Although not a highly complex model, this serves as a solid baseline for future improvements (e.g., advanced models, NLP on description).

<br>
✅ Future Improvements

Incorporate Natural Language Processing (NLP) on the description column

Use feature selection and regularization to improve model accuracy

Try other regression models (Random Forest, Gradient Boosting, etc.)

<br>
📁 Folder Structure
wine-quality-prediction/
├── winemag-data-130k-v2.csv/   # Raw and cleaned dataset files
├── p2.ipynb/                   # Jupyter notebook(s) with code
├── README.md                   # Project documentation


<br>
📌 How to Run

Clone the repository:

git clone https://github.com/yourusername/wine-quality-prediction.git
cd wine-quality-prediction


Install dependencies:

pip install -r requirements.txt


Run the notebook:
Open notebooks/wine_regression.ipynb in Jupyter or VS Code and execute step by step.

<br>
🙌 Acknowledgments

Dataset by zackthoutt

Inspired by real-world wine recommendation systems and rating predictions
