# 📊 InstaLike Insights

InstaLike Insights is a machine learning project aimed at predicting the number of likes an Instagram post might receive. It uses essential engagement metrics like follower count, time since posting, and caption length to estimate performance, making it ideal for understanding basic influencer reach.

## 🛠️ Technologies Used
- Python (Pandas, NumPy, Seaborn, Matplotlib)
- Scikit-learn (Linear Regression, Random Forest, Gradient Boosting, GridSearchCV)
- Jupyter Notebook – for end-to-end development and visualization

## 🔄 Workflow Summary
- Loaded and cleaned the dataset

- Conducted exploratory data analysis (EDA) with visualizations
- Engineered numerical features like Caption Length
- Scaled features using StandardScaler
- Trained and compared multiple regression models
- Tuned Random Forest using GridSearchCV
- Evaluated performance using R² score

## 📌 Features Included
- Followers
- Caption Length 
- Hours Since Posted

## 🎯 Target Variable
- **Likes**

## 📈 Model Performance
- Multiple regression models were trained and evaluated.  
The one with the best performance was selected for final predictions.


## 📁 Project Contents
- `instagram_like_data.csv` – Input dataset
- `insta_like_insights-final-code.ipynb` – Jupyter Notebook with full code
- `README.md` – Project overview and summary
