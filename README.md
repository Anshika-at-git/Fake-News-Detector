# Fake News & Misinformation Detection Using Machine Learning

**"Fighting fake news is not just a technical challenge — it's a national responsibility."**

Hi, I’m **Anshika Singh**, a 4th-semester B.Tech student in CSE (AI & ML), and I built this project out of my deep interest in **Machine Learning**, **NLP**, and most importantly — **national integrity**.

In an age where false information spreads faster than the truth, the need to detect misinformation isn’t just academic — it’s vital to the **mental, digital, and national security** of our country. This project is my small contribution toward that bigger goal.

---

## 📌 Project Overview

This machine learning model helps detect **fake news and misinformation** from article headlines or snippets. It classifies whether a piece of news is likely to be *real* or *fake*, and is especially relevant in today’s context of information overload, digital propaganda, and psychological manipulation.

I was inspired to build this not only to learn ML hands-on, but because I strongly believe that **technological solutions can play a major role in safeguarding national awareness** — something I hope to pursue more deeply through an internship at **DRDO**.

---

## 🧰 Tech Stack

- **Language**: Python  
- **Platform**: Google Colab  
- **Libraries Used**:
  - `pandas` for data manipulation  
  - `TfidfVectorizer` for text feature extraction  
  - `scikit-learn` for ML pipeline  
  - `LogisticRegression` for classification

---

## 📁 Dataset Details

- **Source**: Kaggle Fake and True News Dataset  
- Consists of `fake.csv` and `true.csv`, mostly news from 2016–2017  
- Dataset not uploaded here due to GitHub’s 25MB limit. It was loaded in Colab for training.

---

## 📊 Model Performance

- Achieved **~98% accuracy** on validation data  
- Trained using Logistic Regression with TF-IDF vectors  
- **Limitations**:
  - May not perform well on current 2026 news patterns  
  - Doesn’t capture deep semantic meaning

    | Metric     | Validation Score |
|------------|------------------|
| Accuracy   | 98%              |
| Precision  | 97.5%            |
| Recall     | 98.2%            |
| F1-Score   | 97.8%            |


---

## 🚀 How to Run
1. Clone the repo  
2. Open `FakeNewsDetection.ipynb` in Google Colab  
3. Upload `fake.csv` and `true.csv` from your Kaggle dataset  
4. Run all cells to train the model and get prediction on new input

---

## 🚀 What’s Next?

Although this version doesn’t use BERT or XGBoost yet, I plan to implement both in an upgraded model soon. I’m currently learning these technologies and will release an advanced version once I gain confidence.

This isn’t just a one-time project for me — it’s a stepping stone to a career where I hope to **merge AI with national service**.

---

## 🧠 Relevance to Defense

Fake news is often used as a **psychological weapon**, spreading chaos, confusion, or hate. A tool like this could support defense organizations by:
- Monitoring narrative threats  
- Identifying disinformation campaigns  
- Aiding cyber-intelligence systems
- 
---

## 👩‍💻 Developed By

**Anshika Singh**  
6th Semester, B.Tech CSE (AI & ML)  
Oriental Institute of Science & Technology, RGPV University  
LinkedIn: www.linkedin.com/in/
anshika-singh-4ab153331
