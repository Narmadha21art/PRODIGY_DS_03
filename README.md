# 🐦 Twitter Entity Sentiment Analysis

This project analyzes and visualizes sentiment patterns in social media tweets to understand public opinion and attitudes toward specific topics, brands, or public figures. It utilizes a pre-labeled dataset of tweets and applies data preprocessing, exploratory data analysis (EDA), and sentiment visualization techniques.

## 📁 Dataset

**Source**: [Twitter Entity Sentiment Analysis Dataset on Kaggle](https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis)

The dataset contains tweets labeled with:
- **Entity** – The brand/person/organization being discussed (e.g., Apple, Google).
- **Sentiment** – The sentiment label: `Positive`, `Negative`, `Neutral`, or `Irrelevant`.
- **Tweet** – The actual tweet text.

## 🧠 Objectives

- Clean and preprocess the tweet text for analysis.
- Visualize the overall distribution of sentiment.
- Explore sentiment trends across different entities (brands or topics).
- Generate word clouds to highlight common terms in each sentiment category.
- Optionally, apply VADER sentiment scoring to validate or extend analysis.

## 📊 Features & Analysis

- ✅ Sentiment distribution plot
- ✅ Entity-wise sentiment breakdown (stacked bar graph)
- ✅ Word clouds for `Positive`, `Negative`, and `Neutral` tweets
- ✅ Text preprocessing (removal of URLs, mentions, hashtags, special characters, stopwords)
- ✅ Optional sentiment scoring using `VADER` (TextBlob/VADER can be used for custom scoring)

## 🛠️ Libraries Used

- `Pandas`, `NumPy` – Data handling
- `Matplotlib`, `Seaborn` – Visualization
- `WordCloud` – Generating word clouds
- `NLTK` – Text cleaning and sentiment scoring (VADER)

## 🧪 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
````

2. Install required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn wordcloud nltk
   ```

3. Download the dataset from Kaggle and place it in the project folder as `twitter_training.csv`.

4. Open the notebook:

   ```bash
   jupyter notebook PRODIGY_DS_03.ipynb
   ```

## 📂 Project Structure

```
PRODIGY_DS_03/
│
├── PRODIGY_DS_03.ipynb        # Main analysis notebook
├── twitter_training.csv       # Dataset (you must download and place manually)
├── README.md                  # Project documentation
```

## 📌 Future Improvements

* Deploy the model with live Twitter data using Tweepy or Twitter API.
* Incorporate named entity recognition (NER) to dynamically extract brands/topics.
* Perform time-based sentiment trends.
* Train a custom classifier for sentiment prediction.

## 👤 Author

* **Y. Narmadha** – [GitHub](https://github.com/your-username)
* MCA Student, SITS,Hyderabad

---

📬 For any queries or suggestions, feel free to open an issue or contact me at:
📧 [narmadhayadav33@gmail.com](mailto:narmadhayadav33@gmail.com)


