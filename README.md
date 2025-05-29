# Email Spam Detection (AI Project)

A machine learning project that classifies emails as spam or not using Natural Language Processing.

## 🛠 Technologies Used
- Python
- Scikit-learn
- Pandas
- Jupyter Notebook

## 🔑 Features
- Naive Bayes classification
- Accuracy report
- Predict custom email input

## 📁 Sample Code Snippet
```python
from sklearn.feature_extraction.text import CountVectorizer
from sklearn.naive_bayes import MultinomialNB

model = MultinomialNB()
model.fit(X_train, y_train)
print("Accuracy:", model.score(X_test, y_test))
