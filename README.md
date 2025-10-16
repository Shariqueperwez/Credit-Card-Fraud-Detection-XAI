# Credit-Card-Fraud-Detection-XAI
A machine learning project to detect credit card fraud and explain the predictions using SHAP


# 💳 My Credit Card Fraud Detection Project

Hey there! Welcome to my project. I wanted to build something more than just a simple program—I wanted to create a "smart detective" that could catch credit card fraud. But I didn't want it to be a "black box." I wanted to understand its thought process, and that’s what makes this project special.

This wasn't just about predicting fraud; it was about understanding **why** a transaction looks suspicious.

---

## 🤔 My Journey & The Big Challenge

When I first looked at the data, I hit a wall. Out of almost 300,000 transactions, only about 500 were fraudulent. That's like finding a needle in a giant haystack! 

My biggest challenge was: how do I train a model to catch a "thief" it has barely ever seen? If I wasn't careful, my model would just learn to say "everything is normal" and get 99.8% accuracy, which would be completely useless.

To solve this, I used a cool trick called **SMOTE**. It cleverly created more "fake" (but realistic) fraud examples for my model to practice on. This way, my model got the training it needed to actually become a smart detective.

---

## ✨ What's Cool About This Project?

1.  **A Powerful Detective (XGBoost):** I used a machine learning model called XGBoost. It's known for being incredibly accurate and is often used by winners of data science competitions.

2.  **Understanding the "Why" (Explainable AI):** This is the heart of my project! I used a special library called **SHAP** that lets us peek inside the model's brain. It generates simple charts that explain its decisions. Now, we don't just know *that* a transaction is fraud, we know *why*.



For example, the SHAP plots can tell us things like: *"This transaction was flagged because Feature 'V14' had a really low value, which is a big red flag for fraud."*

---

## 🛠️ Tech I Used

I built this project using some of the most common tools in data science:

* **Language:** Python
* **Data Handling:** Pandas, NumPy
* **Modeling & Prep:** Scikit-learn, XGBoost
* **The Magic Ingredients:** Imbalanced-learn (for SMOTE), SHAP (for the explanations!)
* **Visuals:** Matplotlib, Seaborn

---

## 📂 The Data

The dataset (`creditcard.csv`) for this project is quite large (around 145 MB), so I couldn't upload it directly to GitHub.

You can grab it from the link below.

**[➡️ Download the Dataset Here](https://drive.google.com/file/d/1c337KQ2iX9NQjwNPDa0el6TFhkN3d8Yv/view?usp=sharing)**

**Just a heads-up:** Please download the file and place it in the same folder as the notebook, otherwise the code won't find it!

---

## 🚀 How to Get it Running

Want to see it in action? It's pretty simple:

1.  Download the project files (or clone the repo).
2.  Download the dataset from the link above and put it in the project folder.
3.  Open up the Jupyter Notebook file (`Credit_Card_Fraud_Project.ipynb`).
4.  Run the cells from top to bottom.

And that's it! You'll see the whole process unfold, from cleaning the data to the final, cool-looking explanation charts.
