# 🎵 Music Recommendation System

This is my second project in **Data Science and Machine Learning** as part of my learning journey. I have built a **Music Recommendation System** using various machine learning models to suggest songs based on user listening habits. The dataset for this project was sourced from **Kaggle**.

## 📊 Project Overview

The goal of this project is to recommend songs to users based on their preferences and listening habits. The dataset consists of user interaction data with various features such as song ID, user ID, song popularity, and user-specific metrics. 

## 🔍 Key Steps in the Project

### 1. Data Collection and Preprocessing
- The dataset was obtained from the **Kaggle** platform.
- Handled missing values, duplicates, and ensured data consistency.
- Normalized and standardized features to enhance model performance.

### 2. Exploratory Data Analysis (EDA)
- Conducted analysis to understand user interaction patterns with songs.
- Visualized data using histograms, box plots, and scatter plots to identify trends and outliers.
- Examined correlations between features to identify key factors influencing user preferences.

### 3. Model Building and Evaluation
- **Random Forest Classifier**: Used for its robustness and ability to handle complex data interactions.
- **Logistic Regression**: Applied as a baseline model for binary classification tasks in the recommendation system.
- **K-Nearest Neighbors (KNN)**: Utilized to capture similarity between user preferences based on their listening habits.
- Evaluated the models using metrics such as accuracy, precision, recall, and F1-score.
- Selected the best-performing model based on evaluation metrics for generating song recommendations.

### 4. Recommendation System
- Based on the fitted models, the system recommends songs to users by predicting the likelihood of a user liking a song.
- Personalized song recommendations are made according to user listening history and preferences.

## 📈 Results
The implemented models were able to provide accurate and relevant song recommendations. The **Random Forest Classifier** showed the best performance among the tested models, effectively capturing the complex patterns in the user-song interaction data.

## 🛠️ Tech Stack
- **Python**: Programming language used for analysis and modeling.
- **Pandas & NumPy**: For data manipulation and numerical computations.
- **Matplotlib & Seaborn**: For visualizing data insights and EDA.
- **Scikit-Learn**: For implementing machine learning models and evaluation metrics.

## 🚀 Future Enhancements
- Incorporate collaborative filtering techniques to further improve recommendations.
- Experiment with advanced models like **XGBoost** and **Neural Networks** for better accuracy.
- Implement a user interface for real-time song recommendations based on user input.


## 📢 Acknowledgements
- **Kaggle** for providing the dataset used in this project.
- The **Data Science and Machine Learning Community** for valuable resources and guidance.

