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

This project demonstrates a complete **Data Science workflow** for predicting IMDb movie ratings using regression algorithms.

The project focuses on cleaning and preprocessing movie data, exploring relationships between different movie attributes, engineering useful features, training multiple regression models, and comparing their predictive performance.

The workflow includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, feature importance analysis, and custom movie rating prediction.

---

# 🎯 Objectives

- Analyze the IMDb Movies India dataset
- Perform data preprocessing and cleaning
- Handle missing values
- Encode categorical features
- Train multiple regression models
- Compare model performance
- Predict movie ratings
- Save the trained model using Joblib

---

# 📊 Dataset

The dataset contains information about Indian movies collected from IMDb.

### Features

- Genre
- Director
- Actors
- Duration
- Votes
- Release Year

### Target

- IMDb Movie Rating

---

# 🚀 Project Workflow

- Import Required Libraries
- Load Dataset
- Data Cleaning
- Handle Missing Values
- Exploratory Data Analysis (EDA)
- Data Visualization
- Feature Engineering
- Label Encoding
- Train-Test Split
- Model Training
- Model Evaluation
- Feature Importance Analysis
- Movie Rating Prediction
- Model Saving using Joblib

---

# 📈 Exploratory Data Analysis

The project includes visualizations such as:

- Rating Distribution
- Genre Distribution
- Votes vs Rating
- Correlation Heatmap
- Feature Importance Chart
- Model Performance Comparison

---

# 🤖 Regression Models

The following regression algorithms were implemented and evaluated:

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor

---

# 📊 Model Performance

The models were evaluated using the **R² Score**.

| Model | R² Score | Performance |
|--------|---------:|-------------|
| Linear Regression | **0.0881** | Good Baseline |
| Decision Tree Regressor | **-0.3321** | Poor Performance |
| Random Forest Regressor | **0.3464** | ⭐ Best Performing Model |

🏆 **Best Model:** Random Forest Regressor

---

# 💡 Key Insights

- The **Random Forest Regressor** achieved the best predictive performance among the evaluated models.
- The **number of votes** was one of the most influential features affecting movie ratings.
- Label Encoding enabled categorical variables such as genre, director, and actors to be used by regression models.
- Feature engineering and preprocessing improved overall model performance.
- The project demonstrates how different regression algorithms perform on real-world movie rating data.

---

# 🛠️ Technologies Used

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
├── Movie_Rating_Prediction.ipynb
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
jupyter notebook Movie_Rating_Prediction.ipynb
```

Or open the notebook directly in **Google Colab**.

---

# 📈 Future Improvements

- Improve feature engineering techniques
- Apply Hyperparameter Tuning
- Perform Cross Validation
- Try Gradient Boosting and XGBoost models
- Deploy the model using Streamlit
- Build an interactive Movie Rating Prediction web application

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

If you found this project helpful, don't forget to leave a ⭐ Star!

Made with ❤️ by **Sri Vadshan J**

</div>
