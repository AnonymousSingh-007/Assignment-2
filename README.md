# Assignment-2
📰 News Article Topic Classification – 20 Newsgroups
📌 Overview
This project demonstrates an end-to-end machine learning pipeline for text classification using the 20 Newsgroups dataset. The objective is to classify news articles into one of 20 predefined categories. The pipeline includes steps from text preprocessing to feature extraction, model building, hyperparameter tuning, and performance evaluation.

✅ Project Goals
Build a robust text classification pipeline using Scikit-learn.

Preprocess and clean raw text data.

Extract meaningful features from textual data.

Train and evaluate multiple machine learning models.

Fine-tune the best-performing model.

Provide insights and interpretability from the results.

📚 Dataset
Source: Scikit-learn's fetch_20newsgroups

Categories: 20 distinct newsgroups/topics including politics, tech, sports, religion, and more.

Task: Multi-class classification.

🧠 Pipeline Steps
1. 🔍 Data Exploration & Preprocessing
Loaded data using fetch_20newsgroups.

Explored data distribution, class balance, and content structure.

Removed headers, footers, and quotes for cleaner content.

2. 🧹 Text Preprocessing
Tokenization

Stopword removal

Lowercasing

Lemmatization (via spaCy or NLTK)

Optional: Punctuation and digit removal

3. 🛠️ Feature Extraction
Transformed cleaned text using TF-IDF Vectorization.

Explored n-grams and max features for optimal performance.

4. 🤖 Modeling & Baseline
Implemented baseline models:

Multinomial Naive Bayes

Logistic Regression

Support Vector Machine (SVM)

5. 🧪 Hyperparameter Tuning
Used GridSearchCV and RandomizedSearchCV for:

Regularization strength

Kernel choice

Max features, n-grams, etc.

6. 📈 Model Evaluation
Evaluated using:

Accuracy

F1-score

Confusion Matrix

Classification Report

7. 💬 Interpretation & Insights
Identified the most influential words/features per class.

Compared model performances and provided recommendations.

📊 Evaluation Criteria Checklist

Criteria	Status
Data Wrangling & Preprocessing	✅ Completed
Exploratory Data Analysis	✅ Completed
Feature Engineering	✅ Completed
Model Implementation & Baseline	✅ Completed
Validation & Evaluation	✅ Completed
Hyperparameter Tuning	✅ Completed
Interpretability & Insights	✅ Completed
Code Quality & Documentation	✅ Completed
🚀 How to Run the Project
1. Clone the Repository
git clone https://github.com/yourusername/news-topic-classification.git
cd news-topic-classification

2. Install Dependencies
pip install -r requirements.txt

3. Run the Notebook or Script
If using Jupyter Notebook:

jupyter notebook topic_classification.ipynb
Or run the Python script:

python topic_classification.py
📁 Project Structure
news-topic-classification/
│
├── data/                         # (optional) saved datasets or intermediate data
├── notebooks/                    # Jupyter notebooks
├── topic_classification.py       # Script for running pipeline
├── requirements.txt              # Python dependencies
├── README.md                     # Project overview and instructions
└── reports/                      # Plots, metrics, evaluation outputs
📄 License
This project is open-source and available under the MIT License.
