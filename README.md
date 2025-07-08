# 📰 Fake News Detection Using NLP and Machine Learning

This project applies natural language processing and machine learning techniques to identify fake news articles using a labeled dataset. It processes real-world news text data, performs exploratory analysis, sentiment analysis, and builds classification models to differentiate between real and fake news.

## 🚀 Features

- 📁 Loads and merges `Fake.csv` and `True.csv` datasets
- 🧹 Text preprocessing: lowercasing, punctuation removal, stopwords filtering
- 📊 Exploratory Data Analysis: class distributions, word frequencies, sentiment analysis
- 📦 Feature extraction using TF-IDF
- 🧠 Machine learning model training: Logistic Regression, Naive Bayes, etc.
- 📉 Model evaluation with accuracy, confusion matrix, and classification report
- 📈 Box/violin plots for sentiment comparison between real and fake news

## 🧰 Tech Stack

- Python 3.x
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn
- NLTK (tokenization, stopwords)
- WordCloud
- Jupyter Notebook

## 📁 Dataset

This project uses two CSV files:
- `Fake.csv` – containing fake news articles
- `True.csv` – containing real news articles

Each row contains a news article and metadata.

## 📦 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/fake-news-detector.git
cd fake-news-detector
```

### 2. Create Virtual Environment (optional)

```bash
python -m venv venv
source venv/bin/activate  # macOS/Linux
venv\Scripts\activate   # Windows
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Download NLTK Resources (first-time only)

```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
```

## ▶️ Run the Notebook

```bash
jupyter notebook Fake_news_Detection.ipynb
```

## 📁 Files

| File                        | Description |
|-----------------------------|-------------|
| `Fake_news_Detection.ipynb` | Main notebook for cleaning, analyzing and training the classifier |
| `Fake.csv`, `True.csv`      | Dataset files (input data) |
| `requirements.txt`          | Python dependencies |
| `README.md`                 | Project overview and instructions |

## 📃 License

This project is for academic and educational use.