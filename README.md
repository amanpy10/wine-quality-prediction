# 🍷 Wine Quality Prediction Using Linear Regression

This repository contains a comprehensive analysis and predictive modeling project on the **Wine Reviews** dataset sourced from Kaggle. The primary objective is to predict wine quality ratings using Linear Regression by applying data preprocessing, exploratory data analysis, and machine learning techniques with Python.

---

## 📖 Project Overview

The project workflow includes:

- Cleaning and preprocessing the dataset to handle missing values and transform categorical variables.
- Conducting exploratory data analysis (EDA) to uncover meaningful insights and visualize feature distributions.
- Building and evaluating a Linear Regression model to predict wine quality scores based on relevant features.

---

## 📂 Dataset Details

The dataset consists of over 130,000 wine reviews, with key attributes including:

- `country`: Country of origin
- `province`: Region within the country
- `variety`: Grape variety
- `winery`: Producer name
- `points`: Wine rating (target variable)
- `price`: Wine price
- `description`: Textual description of the wine (not used in modeling)

---

## ⚠️ Dataset Availability

Due to GitHub file size restrictions, the raw dataset CSV file is **not included** in this repository.

### To obtain the dataset:

1. Visit the Kaggle dataset page:  
   [Wine Reviews Dataset on Kaggle](https://www.kaggle.com/datasets/zynicide/wine-reviews)

2. Download the `winemag-data-130k-v2.csv` file.

3. Place the downloaded CSV file into the `data/` directory located at the root of this repository.

---

## 🗂 Repository Structure
```
wine-quality-prediction/
│
├── data/                      # Folder to hold the dataset (not uploaded to GitHub)
│   └── .gitkeep               # Empty placeholder file to keep this folder tracked by Git
│
├── p2.ipynb                   # Jupyter notebook with full analysis and Linear Regression model
│
├── README.md                  # Project documentation with instructions and dataset link
│
└── .gitignore                 # File specifying which files/folders Git should ignore
```
---


## 🛠 Technologies & Libraries

- **Python 3**  
- **Pandas**: Data manipulation and preprocessing  
- **Matplotlib**: Data visualization  
- **Scikit-learn**: Machine learning (Linear Regression)

---

## 🚀 Getting Started

Follow these steps to set up and run the project locally:

1. Clone the repository: git clone https://github.com/yourusername/wine-quality-prediction.git
cd wine-quality-prediction

2.Download the dataset as explained above and place the CSV file in the data/ folder.

3.Install project dependencies:

pip install -r requirements.txt


4.Launch the Jupyter Notebook to explore the analysis and modeling:🙏 Acknowledgments

Dataset provided by zackthoutt
 on Kaggle.

Inspired by data science and machine learning techniques for wine quality prediction.

jupyter notebook p2.ipynb
---
🤝 Contribution & Issues

Contributions, suggestions, and issue reports are warmly welcome. Feel free to open an issue or submit a pull request to enhance the project.
---
Thank you for exploring this project! For questions or collaboration, please contact [negiaman.py@gmail.com] or open an issue.
