# Twitter Sentiment Analysis - NLP Project

This project performs sentiment analysis on tweets using Natural Language Processing (NLP) techniques and a Logistic Regression model. The aim is to classify tweets as **positive** or **negative** based on their content.

---

## ❓ Why Sentiment Analysis Matters

Every day, millions of people express opinions on platforms like Twitter, Reddit, and Facebook. Sentiment analysis allows us to automatically process and classify these opinions as **positive, negative, or neutral** using Natural Language Processing (NLP). This helps businesses, researchers, and organizations gain insights from unstructured text at scale—something that's impossible to do manually.

---

## 🔍 Project Significance

This project demonstrates how to use basic NLP techniques—like tokenization, stopword removal, and TF-IDF vectorization—combined with a **Logistic Regression** model to perform binary sentiment classification on tweets.

Despite its simplicity, Logistic Regression can be quite effective for linearly separable data, making it a great baseline model for sentiment classification tasks.

---

## 💡 Real-World Applications

- **Brand Monitoring**: Track public perception in real-time.
- **Market Research**: Analyze reactions to new products or marketing campaigns.
- **Political Analysis**: Monitor public sentiment around policies or candidates.
- **Customer Support**: Identify and respond to negative feedback promptly.
- **Stock Market Prediction**: Use sentiment signals in financial modeling.

---

## 🧠 Model Used

- **Model**: Logistic Regression (`scikit-learn`)
- **Vectorizer**: TF-IDF
- **Accuracy on Test Data**: **77.6%**

---

## 📊 Workflow

1. **Text Preprocessing**  
   - Lowercasing  
   - Tokenization  
   - Stopword removal  
   - Lemmatization  

2. **Feature Extraction**  
   - TF-IDF vectorization  

3. **Train/Test Split**

4. **Model Training**  
   - Logistic Regression

5. **Model Evaluation**  
   - Accuracy Score

6. **Model Saving**  
   - `pickle`

---

## 📁 Files

- `Twitter_Sentiment_Analysis.ipynb`: Full Colab notebook with code, training, evaluation, and model saving.

---

## 🛠️ Technologies Used

- Python
- pandas, numpy
- scikit-learn
- matplotlib
- Google Colab
- nltk

---

## 🚀 How to Run

```bash
# Option 1: Open in Google Colab
1. Clone the repo or download the notebook.
2. Open `Twitter_Sentiment_Analysis.ipynb` in Google Colab.
3. Run all cells sequentially.

# Option 2: Run Locally
1. Install requirements: pip install -r requirements.txt
2. Open the notebook using Jupyter Notebook or Jupyter Lab.
