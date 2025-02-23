# SENTIMENT-ANALYSIS
COMPANY: CODTECH IT SOLUTIONS

NAME:PRIYADHARSHINI V

INTERN ID: CT08SEW

DOMAIN: DATA ANALYSIS

DURATION: 4 WEEEKS

MENTOR: NEELA SANTOSH


DESCRIPTION:

Description of the Sentiment Analysis Code

This Python script performs **sentiment analysis** on Amazon reviews using **VADER (NLTK)** and **RoBERTa (Transformers)**. It involves data preprocessing, sentiment scoring, visualization, and model evaluation.

---

1. Importing Libraries & Loading Data
- Libraries for **data handling (pandas, numpy), visualization (matplotlib, seaborn), and NLP (NLTK, Transformers)** are imported.
- A dataset of **Amazon reviews** is loaded (`Reviews.csv`), and the first **500 rows** are selected.

---
2. Data Exploration & Visualization
- A **bar plot** is created to show the distribution of **review scores (1-5 stars)**.
- A sample review is **tokenized**, **POS-tagged**, and **named entity recognition (NER)** is performed.

---

3. Sentiment Analysis with VADER (NLTK)
- **VADER SentimentIntensityAnalyzer** assigns **positive, neutral, and negative scores** to text.
- Sentiment scores are computed for each review.
- A **bar plot** shows the correlation between **review scores and compound sentiment scores**.

---

4. Sentiment Analysis with RoBERTa (Transformers)
- The **pre-trained RoBERTa model (`cardiffnlp/twitter-roberta-base-sentiment`)** is used.
- A **function** calculates **negative, neutral, and positive** sentiment scores.
- Sentiment scores are computed for each review and stored in a **DataFrame**.

---

5. Model Comparison & Visualization
- VADER and RoBERTa results are merged.
- **Pair plots** compare sentiment scores across different review scores.
- **Example reviews** with high/low sentiment scores are displayed.

---

6. Sentiment Analysis Pipeline
- The **Hugging Face `pipeline`** is used for quick sentiment classification on example sentences.

This script provides **insights into customer sentiment** using both **rule-based (VADER) and deep learning-based (RoBERTa) approaches?

DESCRIPTION OF TASK:

The task is given as part of a "DATA ANALYSIS-1.pdf" file, presumably as part of a larger internship program.
The main aim is to carry out sentiment analysis on text data. This is to analyze text, for example, tweets or reviews, and find out the emotional tone or attitude conveyed in it (e.g., positive, negative, or neutral).
The work calls for the usage of Natural Language Processing (NLP) algorithms. This implies the use of computer programs to process and comprehend human language, which may involve tasks such as text cleaning, tokenization, feature extraction, and model training.
The deliverable is a notebook illustrating the whole process. This notebook is supposed to present the following:
* Data Preprocessing: Actions undertaken to clean and prepare the text data for analysis. This may include the elimination of unwanted characters, dealing with missing values, or converting the text into a proper format.
* Model Implementation: The specific sentiment analysis model employed, including the algorithm chosen (e.g., Naive Bayes, Support Vector Machines, deep learning models) and its training on the data.
* Insights: The outputs of the analysis, such as interpretation and conclusion made from sentiment scores. This may include data visualization of the trends in sentiments or the top drivers of the sentiments.
The challenge is made available by "CODTECH," presumably the organization or company sponsoring the internship. The photo also states that there will be a "Completion Certificate" once the end date of the internship comes.


