# Skills

## Level 1: Metadata

* **Name:** Shashank Tewari
* **Domain:** Computer Science & Data Science
* **Current Status:** 3rd Year Undergraduate (BMS College of Engineering)
* **CGPA:** 9.2
* **Focus Areas:** Machine Learning, Data Analysis, Software Development
* **Primary Languages:** Python, C++, Java, SQL
* **Core Strengths:** Problem Solving, Data Structures & Algorithms, ML Model Development, Data Visualization

---

## Level 2: Instructions

### 🔧 Programming & Software Development

* Write efficient and modular code in Python, C++, and Java
* Apply Object-Oriented Programming (OOP) concepts
* Use Git & GitHub for version control and project management
* Build backend logic for ML-based applications

---

### 🤖 Machine Learning

* Perform end-to-end ML pipeline:

  * Data preprocessing (cleaning, handling missing values)
  * Feature engineering (domain-based transformations)
* Apply ML algorithms:

  * Linear Regression
  * Logistic Regression
  * Random Forest
* Build recommendation systems using:

  * TF-IDF Vectorization
  * Cosine Similarity
* Evaluate models using:

  * Accuracy
  * Mean Absolute Error (MAE)

---

### 📊 Data Analysis & Visualization

* Analyze large datasets using Pandas and NumPy
* Extract meaningful insights from structured data
* Create visualizations using:

  * Matplotlib
  * Power BI
* Build interactive dashboards (user behavior analysis)

---

### 🌐 Web & ML Deployment

* Build web-based ML applications using:

  * Flask
  * Streamlit
* Deploy ML models with user interfaces
* Handle user inputs and integrate prediction pipelines

---

### 🗄️ Databases

* Work with relational databases:

  * MySQL
* Perform:

  * CRUD operations
  * Query optimization
  * Data retrieval using SQL

---

### ⚙️ Tools & Workflow

* Development Tools:

  * VS Code
  * Jupyter Notebook
  * PyCharm
* Data Tools:

  * Power BI
* Version Control:

  * Git, GitHub

---

## Level 3: Resources & Code

### 🐍 Data Processing (Pandas)

```python
import pandas as pd

df = pd.read_csv("data.csv")
df = df.dropna()
print(df.head())
```

---

### 🤖 Machine Learning Model (Regression)

```python
from sklearn.linear_model import LinearRegression

model = LinearRegression()
model.fit(X_train, y_train)

predictions = model.predict(X_test)
```

---

### 🧠 Recommendation System (TF-IDF)

```python
from sklearn.feature_extraction.text import TfidfVectorizer
from sklearn.metrics.pairwise import cosine_similarity

vectorizer = TfidfVectorizer()
tfidf_matrix = vectorizer.fit_transform(data['text'])

similarity = cosine_similarity(tfidf_matrix)
```

---

### 🌐 Flask Deployment

```python
from flask import Flask

app = Flask(__name__)

@app.route("/")
def home():
    return "ML Model Running"
```

---

### 🚀 Streamlit App

```python
import streamlit as st

st.title("Movie Recommendation System")
st.write("Select a movie to get recommendations")
```

---

### 📊 Visualization (Matplotlib)

```python
import matplotlib.pyplot as plt

plt.plot([1,2,3], [4,5,6])
plt.show()
```

---

### 🗄️ SQL Query

```sql
SELECT * FROM users WHERE age > 25;
```

---

### 🔍 Example ML Pipeline

```python
# Load data
df = pd.read_csv("data.csv")

# Preprocess
df = df.dropna()

# Train model
from sklearn.ensemble import RandomForestClassifier
model = RandomForestClassifier()
model.fit(X_train, y_train)

# Predict
y_pred = model.predict(X_test)
```

---
