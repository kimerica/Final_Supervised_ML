# BBC News Category Classification (Supervised ML)

This project uses supervised machine learning models to classify BBC news articles by category (e.g., tech, business, politics). The goal is to compare multiple models and identify the best performer for text classification.

---

## Dataset

- **Source:** [Kaggle – BBC News Archive](https://www.kaggle.com/datasets/hgultekin/bbcnewsarchive?select=bbc-news-data.csv)
- **Format:** Text + category (label)
- **Size:** 2,225 articles across 5 categories

---

## Tools & Libraries

- **Python Libraries:** `pandas`, `scikit-learn`, `numpy`, `seaborn`, `matplotlib`, `re`
- **Techniques:** TF-IDF Vectorization, Train/Test Split, Model Evaluation
- **Models Compared:**
  - Logistic Regression (One-vs-Rest)
  - Support Vector Machine (SVM)
  - Multinomial Naive Bayes

---

## Workflow

1. Load and clean the BBC dataset
2. Preprocess text using TF-IDF
3. Split into training and test sets
4. Train multiple classifiers
5. Compare models using:
   - Accuracy Score
   - Confusion Matrix
   - Log Loss
6. Predict categories for unseen test data

---

## Results

- **Best Model:** Logistic Regression  
- **Accuracy Scores (on validation set):**
  - Logistic Regression: *Highest accuracy*
  - SVM: *Moderate performance*
  - Naive Bayes: *Lower accuracy*
- **Confusion matrices** and log loss were used for deeper model evaluation.
- Logistic Regression showed the best balance across categories and was least prone to overfitting.
---

## How to Run

1. Clone this repository
2. Ensure required libraries are installed 
3. Run the notebook: `Supervised_Final.ipynb`
4. Follow the cells step-by-step for preprocessing, training, and evaluation

---

## 👤 Author

**Erica Kim**  
Master’s in Data Science – University of Colorado Boulder  
[GitHub Profile](https://github.com/kimerica)
