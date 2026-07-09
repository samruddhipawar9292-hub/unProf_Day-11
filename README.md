# 🛍️ Product Review Sentiment Analysis using TextBlob & VADER

> An NLP project that analyzes customer product reviews and classifies them into **Positive**, **Negative**, or **Neutral** sentiments using **TextBlob** and **VADER Sentiment Analyzer**.

---

## 📌 Project Overview

Customer reviews are one of the most valuable sources of feedback for businesses. Analyzing thousands of reviews manually is difficult, so this project uses **Natural Language Processing (NLP)** techniques to automatically determine the sentiment of product reviews.

The project compares two popular rule-based sentiment analysis libraries:

- **TextBlob**
- **VADER Sentiment Analyzer**

The results are visualized using bar charts and pie charts to understand overall customer satisfaction.

---

## 🎯 Objectives

- Load and preprocess customer review data.
- Perform Exploratory Data Analysis (EDA).
- Analyze review sentiment using **TextBlob**.
- Analyze review sentiment using **VADER**.
- Classify reviews as:
  - 😊 Positive
  - 😐 Neutral
  - 😠 Negative
- Compare both sentiment analyzers.
- Visualize sentiment distribution.
- Export the final analyzed dataset.

---

## 📂 Dataset

**Dataset Name**

Women's E-Commerce Clothing Reviews Dataset

### Dataset Features

- Review Text
- Rating
- Recommended Indicator
- Customer Age
- Product Category
- Department
- Clothing Class

For this project, **100 reviews** were randomly sampled after data cleaning.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- NLTK
- TextBlob
- VADER Sentiment Analyzer
- Jupyter Notebook

---

# 🔄 Project Workflow

```
Dataset
   │
   ▼
Data Cleaning
   │
   ▼
Exploratory Data Analysis
   │
   ▼
TextBlob Sentiment Analysis
   │
   ▼
VADER Sentiment Analysis
   │
   ▼
Compare Both Models
   │
   ▼
Visualization
   │
   ▼
Export Final Dataset
```

---

# 📊 Exploratory Data Analysis

The following analyses were performed:

- Dataset Information
- Missing Value Analysis
- Duplicate Removal
- Rating Distribution
- Recommendation Distribution
- Review Length Analysis
- Top 10 Most Frequent Words

---

# 😊 TextBlob Sentiment Analysis

TextBlob calculates a **polarity score** between **-1** and **+1**.

| Polarity | Sentiment |
|----------|-----------|
| > 0 | Positive |
| < 0 | Negative |
| = 0 | Neutral |

The project classifies every review using the polarity score.

---

# 😊 VADER Sentiment Analysis

VADER uses the **Compound Score** for sentiment classification.

| Compound Score | Sentiment |
|---------------|-----------|
| ≥ 0.05 | Positive |
| ≤ -0.05 | Negative |
| Otherwise | Neutral |

VADER performs particularly well on short customer reviews.

---

# 📈 Visualizations

The project includes:

- Rating Distribution
- Recommendation Distribution
- Review Length Histogram
- Top Frequent Words
- TextBlob Sentiment Bar Chart
- TextBlob Pie Chart
- VADER Sentiment Bar Chart
- VADER Pie Chart
- TextBlob vs VADER Comparison Chart

---

# 📋 Final Dataset

The final dataset contains the following columns:

| Column |
|---------|
| Review Text |
| Rating |
| Recommended IND |
| Review Length |
| Polarity |
| Sentiment |
| VADER Score |
| VADER Sentiment |

---

# 📊 Sample Output

```
Total Reviews : 100

TextBlob

Positive : 72

Negative : 18

Neutral : 10

----------------------------

VADER

Positive : 69

Negative : 20

Neutral : 11
```

---

# 🚀 How to Run

### Clone Repository

```bash
git clone https://github.com/your-username/Product-Review-Sentiment-Analysis.git
```

### Move to Project Folder

```bash
cd Product-Review-Sentiment-Analysis
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
notebook.ipynb
```

Run all cells.

---

# 📚 Skills Demonstrated

- Natural Language Processing (NLP)
- Data Cleaning
- Exploratory Data Analysis
- Rule-Based Sentiment Analysis
- TextBlob
- VADER
- Data Visualization
- Python Programming
- Feature Engineering
- Git & GitHub

---

# 💡 Future Improvements

- Build a Streamlit Web Application
- Train a Machine Learning Sentiment Classifier
- Implement Deep Learning using LSTM
- Use Transformer Models (BERT/RoBERTa)
- Deploy on Render or Hugging Face Spaces
- Create an Interactive Dashboard

---

# 🎓 Learning Outcomes

Through this project, I learned:

- How sentiment analysis works
- Difference between TextBlob and VADER
- Rule-based NLP techniques
- Customer review analysis
- Visualization of sentiment results
- Building an end-to-end NLP project

---

# 👨‍💻 Author

**Samruddhi Pawar**

B.Tech IT Student

Passionate about Machine Learning, Data Science, and Natural Language Processing.

---

# ⭐ If you found this project useful, don't forget to give it a Star!
