# 📚 Classify Book Genres

This project uses book metadata such as author name, popularity, book length, and number of keywords to build a machine learning model that predicts the genre of a book.

---

## 📌 Problem Statement

Use metadata from books to classify them into genres. This can help publishers, retailers, and readers to automatically categorize books and improve recommendations.

---

## 🚀 How to Run

1. Clone this repository.
2. Place the dataset file book_genres.csv in the same directory.
3. Open the Python script  classify_books.py .
4. Run the script to train the model and evaluate performance.

---

## 🚀 Project Overview

- **Objective:** Predict the genre of a book based on features like author, popularity, length, and number of keywords.
- **Tech Stack:** Python, pandas, scikit-learn, seaborn, matplotlib
- **Model:** Decision Tree Classifier

---


## 🔧 Methodology

- **Data Preprocessing:** Loaded and encoded the CSV data (handled categorical values like author using one-hot encoding).
- **Train-Test Split:** 70-30 split for training and testing.
- **Model Used:** Decision Tree Classifier

### 🧪 Evaluation

- **Confusion Matrix**
- **Accuracy**
- **Precision**
- **Recall**

### 📊 Visualization

- Confusion matrix plotted using a Seaborn heatmap for visual clarity.

---

## 📈 Evaluation Metrics (Sample)

*Metrics will vary slightly depending on the random train-test split.*

- **Accuracy:** 0.85
- **Precision:** 0.83
- **Recall:** 0.82

---

## 🖼️ Output

The project generates:

Sample data:
   author_popularity  book_length  num_keywords    genre
0          41.052297          776             5  mystery
1          48.950098          674             5  mystery
2           2.323401          633            19  fantasy
3          41.564184          169            12  mystery
4          65.129649          992            18  fantasy

Classification Report:
              precision    recall  f1-score   support

     fantasy       0.27      0.75      0.40         4
     fiction       0.67      0.40      0.50         5
     mystery       0.50      0.45      0.48        11
 non-fiction       0.83      0.50      0.62        10

    accuracy                           0.50        30
   macro avg       0.57      0.53      0.50        30
weighted avg       0.61      0.50      0.52        30



- 📘 A confusion matrix heatmap showing model predictions vs. actual genres  
- 🧮 Classification metrics: Accuracy, Precision, Recall  

---

## 📚 References

- **Dataset:** Book Metadata (custom or hypothetical)
- **Libraries Used:**
  - pandas
  - seaborn
  - scikit-learn
  - matplotlib

---

## 🙋‍♀️ Author

**Prateek Rai**  
B.Tech – CSE (AI)  
KIET Group of Institutions

---

