
# Twitter Sentiment Analysis

This project performs sentiment analysis on tweets using the Sentiment140 dataset. It demonstrates how natural language processing (NLP) techniques can be used to classify text data into positive, negative, or neutral sentiments.

---

## 📊 Dataset

We use the **Sentiment140** dataset from Kaggle, which contains 1.6 million labeled tweets.

* **Dataset URL**: [https://www.kaggle.com/datasets/kazanova/sentiment140](https://www.kaggle.com/datasets/kazanova/sentiment140)
* **Columns**:

  * `target`: Sentiment label (0 = negative, 4 = positive)
  * `text`: Tweet content

---

## 🚀 Features

* End-to-end NLP pipeline: data loading, preprocessing, vectorization, and modeling
* Multiple model training: Naive Bayes, Logistic Regression, etc.
* Evaluation using accuracy, confusion matrix, and classification report
* Optional exploratory data analysis (EDA) and visualization

---

## 🛠️ Project Structure

```
.
├── twitter_sentiments.ipynb     # Main notebook
├── README.md                    # Project overview
├── /data                        # Folder to place the dataset CSV (after extraction)
└── requirements.txt             # (Optional) Python dependencies
```

---

## 🧰 Tech Stack

* Python 3.x
* Pandas, NumPy
* Scikit-learn
* NLTK or spaCy (for preprocessing)
* Matplotlib, Seaborn (for visualizations)

---

## 📦 Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/twitter-sentiment-analysis.git
   cd twitter-sentiment-analysis
   ```

2. (Optional) Create and activate a virtual environment:

   ```bash
   python -m venv venv
   source venv/bin/activate  # or `venv\Scripts\activate` on Windows
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Download the dataset:

   * Go to [Sentiment140 Kaggle Page](https://www.kaggle.com/datasets/kazanova/sentiment140)
   * Download and extract the CSV into the `/data` folder.

---

## 🧪 How to Run

1. Open the Jupyter Notebook:

   ```bash
   jupyter notebook twitter_sentiments.ipynb
   ```

2. Run all cells in order. Follow inline instructions if present.

---

## 📈 Results

* Accuracy: \~85–90% depending on the model
* Example output:

  * Positive: "I love this new phone!"
  * Negative: "Ugh, Monday mornings are the worst."

---

## 📚 Future Improvements

* Integrate BERT or LSTM for deep learning-based sentiment analysis
* Deploy model as a REST API using Flask or FastAPI
* Add real-time tweet scraping via Twitter API

---

## 📄 License

This project is licensed under the MIT License.

