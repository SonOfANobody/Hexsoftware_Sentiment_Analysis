## Multi-Platform Sentiment Analysis 🚀

### 📌 Project Overview

This project was developed during my **Machine Learning Internship at HexSoftware**. The goal was to build a Natural Language Processing (NLP) system capable of analyzing and categorizing the emotional tone of social media text from **Twitter, Facebook, and Instagram**.

By understanding whether a post is **Positive, Negative, or Neutral**, businesses can better interpret customer feedback and manage their online reputation effectively.

## 📊 Dataset Description

The dataset consists of approximately 500 social media posts. Key features include:

- **Text:** The raw content of the post.
 
- **Sentiment:** The target label (Positive, Neutral, Negative).

- **Platform:** The source of the post (Twitter, Facebook, Instagram).

- **Metadata:** Year, Month, Day, and Time of Tweet.

## 🛠️ Tech Stack

- **Language:** Python

- **Libraries:**

- `Pandas` & `NumPy` (Data Manipulation)

- `Matplotlib` & `Seaborn` (Data Visualization)

- `NLTK` & `Re` (Text Preprocessing)

- `Scikit-learn` (Machine Learning)

## ⚙️ Project Pipeline

### 1. Exploratory Data Analysis (EDA)

I performed a deep dive into the data to understand distributions and patterns.

- Visualized sentiment balance across different platforms.

- Analyzed the relationship between text length and emotional tone.

- Observed posting patterns based on the time of day.

### 2. Text Preprocessing

Raw social media text is "noisy." I built a 4-step cleaning pipeline:

1. **Lowercasing:** Standardized all text to lowercase.

2. **Punctuation Removal:** Stripped special characters and symbols using Regex.

3. **Number Removal:** Removed digits that don't contribute to sentiment.

4. **Stopword Removal:** Filtered out common non-informative words (e.g., "the", "is") using NLTK.

### 3. Feature Engineering & Modeling

- **Vectorization:** Transformed cleaned text into numerical format using TF-IDF.

- **Modeling:** Trained a Logistic Regression classifier to predict sentiment categories.

## 🚀 How to Run

1. Clone this repository:
  
bash
    
git clone (https://github.com/your-username/sentiment-analysis-hexsoftware.git)

Install dependencies:

Bash

pip install -r requirements.txt

Run the analysis:

Bash

python main.py

## 📈 Key Findings

Neutral sentiment is the most frequent in the dataset.

Negative posts tend to have a slightly higher character count than positive ones.

Instagram and Facebook showed a highly similar distribution of emotional tones.

## 🤝 Acknowledgments

Special thanks to HexSoftware for providing the platform and guidance to work on this internship project.
