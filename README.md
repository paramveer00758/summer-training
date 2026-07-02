# 🚀 Beginner Machine Learning & Data Projects

Welcome to this beginner-friendly projects repo! This repository contains two hands-on data projects designed to learn data analysis, visualization, and machine learning using simple Python tools.

---

## 📊 Project 1: Titanic Survival Analysis (Data Analytics)

### 🔹 What is this project about?
In this project, we look at the real-world list of passengers who were on the famous **Titanic** ship. Our goal is to clean up the data, make colorful charts, and discover hidden patterns about who was more likely to survive the shipwreck.

### 🔹 Core Steps (The Workflow):
1. **Data Loading:** Bringing the Titanic table (CSV file) into Python using a library called `pandas`.
2. **Data Cleaning:** Fixing missing details. For example, if a passenger's age is missing, we fill it in with the middle (median) age of everyone else. We also remove messy or empty columns.
3. **Data Manipulation:** Creating helpful new information. We add up family members to find out the total `FamilySize` and check if a passenger was traveling completely alone.
4. **Exploratory Data Analysis (EDA):** Drawing charts using `matplotlib` and `seaborn` to answer questions visually.
5. **Encoding:** Converting text words (like "male" and "female") into simple numbers (0 and 1) so computers can read them easily.

### 📈 Key Insights Discovered:
* **The "Women & Children First" rule was real:** Women had a much higher survival percentage than men.
* **Money mattered:** Passengers who paid a higher ticket fare had a better chance of being saved.

---

## 🏡 Project 2: California Housing Price Prediction (Machine Learning)

### 🔹 What is this project about?
In this project, we move into **Machine Learning**. We take a dataset containing information about neighborhoods in California (like average income, number of rooms, and location) and train a smart computer model to predict the average house price in those areas.

### 🔹 Core Steps (The Workflow):
1. **Explore the Data:** Look at a correlation heatmap to see which features change together (e.g., higher income usually means higher house prices).
2. **Train/Test Split:** We split our data into two parts:
   * **80% Training Data:** Used to let the computer practice and learn.
   * **20% Testing Data:** Kept secret. We use it at the very end to test if the computer actually learned or just memorized answers.
3. **Feature Scaling (StandardScaler):** We bring all numbers to a similar scale. Without this, a large number like population (e.g., 2,000) might confuse the model into ignoring a small but important number like income (e.g., 5).
4. **Linear Regression:** This is our algorithm. It automatically draws a "line of best fit" through the data points to make predictions.
5. **Evaluation (Testing the Model):**
   * **Mean Squared Error (MSE):** Measures how close the predictions were to the real prices. Smaller numbers mean fewer mistakes!
   * **R-squared (R2) Score:** Tells us how much of the pricing pattern our model understood. A score of 0.58 means our model successfully figured out about 58% of the patterns.

---

## 🛠️ Tools & Libraries Used
* **Pandas:** Used like an interactive Excel spreadsheet to hold and clean tables of data.
* **Matplotlib & Seaborn:** Used to design clean, visual charts, bars, and histograms.
* **Scikit-Learn:** The library that handles the math behind splitting data, scaling numbers, and training the machine learning model.

## 🚀 How to Run These in Google Colab
1. Open [Google Colab](https://colab.research.google.com/) in your web browser.
2. Create a **New Notebook**.
3. Copy the Python code cells provided for either project into the Colab blocks.
4. Press the **Play button** ▶️ on the left of each cell to run the code step-by-step and see the results instantly!
