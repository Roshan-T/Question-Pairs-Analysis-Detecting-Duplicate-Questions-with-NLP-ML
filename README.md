Question Pairs Analysis: Detecting Duplicate Questions with NLP & ML

🚀 Project Overview

This project analyzes the Question Pairs dataset to detect duplicate questions using Natural Language Processing (NLP) and machine learning techniques. Through comprehensive Exploratory Data Analysis (EDA) and feature extraction, we gain insights into patterns that distinguish duplicate and non-duplicate questions.

📌 Key Features

Exploratory Data Analysis (EDA): Visualizing and understanding the dataset.

Text Preprocessing: Cleaning and normalizing question text.

Feature Engineering: Extracting meaningful linguistic and semantic features.

Similarity Measures: Utilizing distance metrics and embeddings for comparison.

Machine Learning Models (optional): Predicting duplicate questions using ML algorithms.

📂 Dataset Details

The dataset consists of question pairs labeled as either duplicate (1) or non-duplicate (0).

Columns:

question1, question2: The pair of questions to analyze.

is_duplicate: A binary label indicating duplication.

qid1, qid2: Unique identifiers for each question.

🛠️ Technologies Used

Python: Core programming language.

Pandas, NumPy: Data manipulation and analysis.

Matplotlib, Seaborn, Plotly: Data visualization.

NLTK, BeautifulSoup: Text preprocessing.

Scikit-learn, XGBoost (optional): Machine learning models.

📊 Exploratory Data Analysis (EDA)

Word Clouds: Visualizing frequently used words in duplicate and non-duplicate questions.

Statistical Distribution Analysis: Understanding word counts, sentence structures, and punctuation usage.

t-SNE Visualizations: Exploring high-dimensional feature spaces.

Pairwise Distance Metrics: Assessing textual similarity using various methods.

🏗️ Feature Engineering

Lexical Similarity: Jaccard similarity, Cosine similarity.

NLP Embeddings: Word2Vec, TF-IDF, or Sentence Transformers.

String Distance Metrics: Levenshtein distance, Damerau-Levenshtein distance.

Syntactic Parsing: Analyzing grammatical structures for differentiation.

🔥 How to Run the Project

Clone the repository

Install required dependencies:

pip install -r requirements.txt

Open the Jupyter Notebook:

jupyter notebook QUORA.ipynb

📈 Insights & Findings

Duplicate questions often share similar structures and key phrases.

Common stop words and phrasing patterns appear frequently in duplicate pairs.

Combining lexical, syntactic, and semantic features enhances model performance.

