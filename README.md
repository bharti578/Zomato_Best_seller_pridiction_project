# Zomato_Best_seller_pridiction_project
Predicting if a food item on Zomato will be a bestseller using ML models like Random Forest and Decision Tree.

# Zomato Bestseller Prediction - Logistic Regression Project

## Overview

This project focuses on predicting whether a food item on Zomato will become a "bestseller" or not.  
I used a Logistic Regression model to analyze different features like price, user ratings, number of votes, and average restaurant/city ratings to make this prediction.

The main goal was to explore how basic machine learning can help understand food popularity trends on platforms like Zomato.

---

## Problem Statement

On food delivery platforms like Zomato, only a few dishes are tagged as "Bestseller" or "Must Try", while thousands of others are not.  
But what makes those popular dishes stand out? Can we predict future bestsellers using data?

This project aims to build a model that can predict whether a dish will become a bestseller based on available information.

---

## Dataset Description

The dataset contains the following key columns:

- `Item_Name`: Name of the food item  
- `Price`: Price of the item  
- `Rating`: User rating  
- `Votes`: Number of user votes  
- `Avg_Rating_Restaurant`: Average rating of the restaurant  
- `Avg_Rating_City`: Average rating in that city  
- `Best_Seller`: Target column (1 = Bestseller, 0 = Not)

The target column was cleaned and converted into binary labels:
- 1 → "BESTSELLER" or "MUST TRY"
- 0 → Others

---

## Model Used

I used **Logistic Regression**, which is a simple and interpretable model for binary classification problems.  
It helped me understand how features like price, rating, and votes affect the popularity of a food item.

---

## Model Performance

Here are the evaluation results of the Logistic Regression model:

- **Accuracy:** 85.1%
- **Confusion Matrix:**
- - **Precision (Bestseller - class 1):** 0.23  
- **Recall (Bestseller - class 1):** 0.68  
- **F1 Score (Bestseller):** 0.34

The model was able to correctly detect many bestsellers (high recall), but it also predicted some wrong ones (low precision), which is expected in imbalanced datasets.

---

## 📚 Key Learnings

- Logistic Regression can be a good starting point for binary classification problems.  
- Class imbalance affects precision a lot — more advanced models or techniques like oversampling may help.  
- Simple models also provide useful insights through feature coefficients.

---

## 🚀 Future Improvements

- Try other classification models like Random Forest or XGBoost  
- Balance the dataset using SMOTE or other sampling techniques  
- Deploy the model using Streamlit for live predictions

---

## 🙋‍♀️ About Me

I'm **Bharti Kushwaha**, a Data Science enthusiast and recent IT graduate.  
I’m building real-world ML projects to gain practical experience and grow in the field.

🔗 https://www.linkedin.com/in/bhartikushwah/

