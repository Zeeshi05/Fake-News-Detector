

# 📰 Fake News Detection AI Project

## 🚀 Overview

In today’s digital age, misinformation spreads faster than ever. Fake news can influence opinions, spark controversy, and even disrupt societies. **This project leverages machine learning to help you distinguish real news from fake news—instantly and interactively!**

---

## 🎯 Project Highlights

- **Robust ML Models:** Trained Naive Bayes and Random Forest classifiers for high-accuracy detection.
- **Interactive Gradio App:** Try the models live in your browser—no coding needed!
- **Comprehensive EDA:** Visualizations and insights into what separates fake from real news.
- **Transparent \& Reproducible:** Clean, well-commented code and clear instructions.

---

## 📊 Why Does Fake News Matter?

> “The problem with fake news is that it can be very convincing, and people may believe it to be true without questioning its authenticity. This can lead to a range of negative consequences.”
> — *Project Motivation*

Fake news can:

- Mislead the public
- Influence elections
- Damage reputations
- Undermine trust in media

---

## 🛠️ Features

- **Data Cleaning \& Preprocessing:** Handles missing values and combines relevant text features.
- **Exploratory Data Analysis:** Visualizes label distributions, word clouds, and more.
- **Bag-of-Words Vectorization:** Converts news text into ML-friendly format.
- **Model Training \& Evaluation:** Includes accuracy, precision, recall, F1-score, and confusion matrices.
- **Gradio Web Interface:** Paste your own news and get instant predictions with model confidence!

---

## 📦 Dataset

- **Source:** [WELFake_Dataset.csv](https://www.kaggle.com/datasets/saurabhshahane/fake-news-classification)
- **Size:** 72,134 news articles
- **Columns:** title, text, label (1 = Real, 0 = Fake)

---

## 💻 Quickstart

1. **Clone the Repo**

```bash
git clone https://github.com/Zeeshi05/Fake-News-Detector
cd FakeNewsDetectionAI
```

2. **Install Requirements**

```bash
pip install -r requirements.txt
```

3. **Download the Dataset**
    - Place `WELFake_Dataset.csv` in the project root.
4. **Run the Notebook**
    - Open `FakeNewsDetection_AIProject.ipynb` in [Google Colab](https://colab.research.google.com/drive/1VKuDHoSJ6UK8SWQKwfJ4XsKz8XJoADM3?authuser=0#scrollTo=-vD4-g0z3XAo/) or Jupyter and run all cells.
5. **Try the Gradio App!**
    - Run the Gradio cell in the notebook.
    - Paste any news article to get a real-time prediction.

---

## 🧠 Model Performance

| Model | Accuracy | Precision | Recall | F1-Score |
| :-- | :-- | :-- | :-- | :-- |
| Naive Bayes | ~89% | High | High | High |
| Random Forest | ~94% | High | High | High |

*Random Forest achieves the highest accuracy!*

---

## 🌐 Live Demo

[

---

## 🏗️ Project Structure

```
├── FakeNewsDetection_AIProject.ipynb  # Main notebook
├── WELFake_Dataset.csv                # Dataset (not included)
├── README.md                          # This file!
├── requirements.txt                   # Required Python packages
├── models/                            # Saved ML models (after training)
```


---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to fork the repo and submit a pull request.

---

## 📢 Credits

- **Dataset:** [Saurabh Shahane on Kaggle](https://www.kaggle.com/datasets/saurabhshahane/fake-news-classification)
- **Developed by:** [Muhammad Zeeshan]

---

**Let’s fight fake news, one article at a time!**

---

*Star ⭐ this repo if you find it useful!*

---


