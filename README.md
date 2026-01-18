# Movie Review Sentiment Analysis 🎬📝

A beginner-friendly Machine Learning project that classifies movie reviews as **positive** or **negative** using Natural Language Processing (NLP) techniques.

---

## 📌 Problem Statement

With the growing number of online movie reviews, it becomes difficult to manually analyze public opinion. This project aims to automatically determine whether a given movie review expresses a **positive** or **negative** sentiment using Machine Learning.

---

## 📊 Dataset

* **Dataset Used:** IMDb Movie Reviews Dataset
  https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews
  
* **Description:** A collection of labeled movie reviews categorized as positive or negative.

---

## ⚙️ Approach

The project follows a complete end-to-end Machine Learning pipeline:

1. **Text Preprocessing**

   * Lowercasing
   * Tokenization
   * Stopword removal
   * Cleaning special characters
   * Lemmatization

2. **Feature Extraction**

   * Bag of Words (BoW) & ngrams using CountVectorizer 

3. **Model Training**

   * Machine Learning classifier (Naive Bayes and Random Forest Classifier) trained on processed text data

4. **Evaluation**

   * Accuracy score
   * Confusion Matrix
---

## 📈 Results

* Achieved good accuracy on test data
* 84% by Random Forest and 85% by Multinomial Naive Bayes
* Model successfully classifies unseen movie reviews


---

## 🛠️ Tools & Technologies

* Python
* Scikit-learn
* Pandas
* NumPy
* NLTK
* Kaggle Notebook

---

## 📂 Project Structure

```
movie-review-sentiment-analysis/
│
├── sentiment_analysis.ipynb
├── README.md
└── dataset/
```

---

## 🔗 Notebook

* Kaggle Notebook: https://www.kaggle.com/code/amisha1571/step-by-step-movie-review-sentiment-analysis

---

## 🚀 Future Improvements

* Try TF-IDF or Word Embeddings
* Experiment with different ML models
* Deploy using Flask or Streamlit

---

## 🙌 Conclusion

This project demonstrates the basics of NLP and Machine Learning by building a sentiment analysis system from scratch. It is ideal for beginners looking to understand text preprocessing, feature extraction, and model evaluation.

---

⭐ If you find this project helpful, feel free to star the repository!
