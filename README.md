# 🍽️ Sentiment Analysis on Restaurant Reviews

## 📌 Overview
This project uses **Natural Language Processing (NLP)** and **Machine Learning** to classify restaurant reviews as **positive** or **negative**.  
It applies multiple models, starting with **Multinomial Naive Bayes (90% accuracy)** and further experiments with **Random Forest, Gradient Boosting, and BiLSTM** for improvements.  

---

## 🛠 Tech Stack
- Python  
- Scikit-learn, Pandas, NumPy  
- NLTK (text preprocessing, stopwords)  
- Matplotlib, Seaborn (visualization)  

---

## 📂 Dataset
The dataset contains customer restaurant reviews with text labels (`positive` or `negative`).  
✅ Dataset is included in this repository as `dataset.csv`.  

---

## ⚙️ Preprocessing
- Text cleaning (removing punctuation, lowercasing)  
- Tokenization & stopword removal  
- Lemmatization  
- Bag-of-Words & TF-IDF vectorization  

---

## 🚀 Models Implemented
1. **Multinomial Naive Bayes** → **90% accuracy**  
2. **Random Forest** → tuned with GridSearchCV  
3. **Gradient Boosting** → improved classification performance  
4. **BiLSTM** → deep learning approach for sequence modeling  

---

## 📊 Results
- **Naive Bayes** performed well on sparse text data.  
- **Ensemble models** improved robustness.  
- **BiLSTM** achieved the best contextual understanding but required more compute.  

---

## 🧑‍💻 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/riyakansal04/sentiment-analysis-restaurant-reviews.git
   cd sentiment-analysis-restaurant-reviews
   
2. Install dependencies:
    ```bash
    pip install -r requirements.txt

3. Run the Jupyter Notebook:
    ```bash
    jupyter notebook sentiment_analysis.ipynb

---

##  📌 Future Work
Deploy as a web app using Flask/Streamlit
Extend dataset to multi-class (e.g., very positive, neutral, very negative)
Integrate into a real-time review monitoring dashboard

## 👩‍💻 Author
**Riya Kansal**  
[LinkedIn](https://www.linkedin.com/in/riya-kansal-963042268/) • [GitHub](https://github.com/riyakansal04)
