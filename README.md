# 🎬 Movie Rating Prediction | Data Science Project

> A Data Science project that predicts IMDb movie ratings using regression algorithms based on movie attributes such as genre, director, actors, votes, duration, and release year.

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Data Science](https://img.shields.io/badge/Data-Science-0A66C2?style=for-the-badge)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-success?style=for-the-badge)

</div>

---

# 📌 Overview

This project demonstrates a complete **Data Science workflow** by predicting IMDb movie ratings using regression algorithms.

The objective is to analyze movie-related attributes, preprocess the dataset, engineer meaningful features, and build predictive models capable of estimating movie ratings.

The project covers the complete Data Science lifecycle, including data preprocessing, visualization, feature engineering, model training, evaluation, prediction, and model persistence.

---

# 🎯 Objectives

- Analyze the IMDb Movies India dataset
- Clean and preprocess the data
- Perform feature engineering
- Encode categorical variables
- Train multiple regression models
- Compare model performance
- Predict movie ratings

---

# 📊 Dataset

The dataset contains information about Indian movies collected from IMDb.

### Features

- Genre
- Director
- Actor Names
- Duration
- Number of Votes
- Release Year

### Target

- IMDb Movie Rating

---

# 🚀 Project Workflow

- Data Loading
- Data Cleaning
- Handling Missing Values
- Exploratory Data Analysis (EDA)
- Data Visualization
- Feature Engineering
- Label Encoding
- Model Training
- Model Evaluation
- Rating Prediction
- Model Saving using Joblib

---

# 📈 Exploratory Data Analysis

The project includes visualizations such as:

- Rating Distribution
- Genre Analysis
- Votes vs Rating
- Correlation Heatmap
- Model Performance Comparison
- Feature Importance Analysis

---

# 🤖 Regression Models

The following regression models were implemented and compared:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

---

# 📊 Model Performance

The models were evaluated using the **R² Score**.

| Model | Performance |
|--------|------------:|
| Linear Regression | Good Baseline |
| Decision Tree Regressor | Improved Performance |
| Random Forest Regressor | ⭐ Best Performing Model |

**🏆 Best Model:** Random Forest Regressor

---

# 💡 Key Insights

- The number of votes was one of the most influential features affecting movie ratings.
- Feature engineering and label encoding improved model performance.
- Random Forest Regressor produced the most accurate predictions among the evaluated models.
- Data visualization helped identify relationships between movie attributes and ratings.

---

# 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Joblib
- Google Colab

---

# 📂 Project Structure

```text
Movie-Rating-Prediction/
│
├── IMDb Movies India.csv
├── MOVIE_RATING_PREDICTION.ipynb
└── README.md
```

---

# ▶️ Running the Project

### Clone the Repository

```bash
git clone https://github.com/vadshan30/Movie-Rating-Prediction.git
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib scikit-learn joblib
```

### Launch the Notebook

```bash
jupyter notebook MOVIE_RATING_PREDICTION.ipynb
```

or open it directly in **Google Colab**.

---

# 📈 Future Improvements

- Hyperparameter Tuning
- Cross Validation
- Advanced Feature Engineering
- Interactive Dashboard
- Streamlit Web Application
- Model Deployment using Flask/FastAPI

---

# 👨‍💻 Author

**Sri Vadshan J**

**B.Tech – Artificial Intelligence & Data Science**

- GitHub: https://github.com/vadshan30
- LinkedIn: https://www.linkedin.com/in/sri-vadshan-47a84a327

---

# ⭐ Support

If you found this project useful:

- ⭐ Star this repository
- 🍴 Fork the repository
- 💡 Suggest improvements
- 🐞 Report issues

---

<div align="center">

### 🎬 Thank you for visiting this repository!

**If you found this project helpful, don't forget to leave a ⭐ Star!**

Made with ❤️ by **Sri Vadshan J**

</div>
