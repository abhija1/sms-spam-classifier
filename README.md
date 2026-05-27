# Email/SMS Spam Classifier

## 📌 Project Overview
This is an end-to-end Machine Learning project that classifies messages as either "Spam" or "Ham" (Legitimate). 

## 🛠️ Tech Stack & Libraries Used
* **Language:** Python
* **NLP & Text Preprocessing:** NLTK, Scikit-Learn (TF-IDF Vectorizer)
* **ML Algorithms:** Multinomial Naive Bayes (Best performing model)
* **Web Framework:** Streamlit
* **Deployment:** Heroku / Render

## 📊 Workflow & Steps
1. **Data Cleaning:** Handled missing values, dropped unnecessary columns, and removed duplicates.
2. **EDA:** Analyzed message lengths, word counts, and generated Word Clouds for spam/ham messages.
3. **Text Preprocessing:** Converted text to lowercase, tokenized, removed special characters/stopwords/punctuations, and applied stemming.
4. **Model Building & Tuning:** Evaluated multiple classifiers (Naive Bayes, Random Forest, SVM, etc.). Multinomial Naive Bayes yielded the best combination of precision and accuracy.

## 🚀 How to Run Locally
1. Clone this repository.
2. Install dependencies using `pip install -r requirements.txt`.
3. Run the web app using `streamlit run app.py`.
