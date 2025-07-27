# 📈 Event-Driven Stock Prediction Using NLP & Machine Learning

## 🔍 Overview
This project analyzes real-time news headlines and predicts stock price movement based on sentiment analysis. It demonstrates how external events (news) can impact stock trends using Natural Language Processing and machine learning classification techniques.

## ⚙️ Tech Stack
- Python 3.8+
- Pandas, NumPy – Data handling
- NLTK, TextBlob – Sentiment analysis
- Scikit-learn – ML algorithms (Random Forest, Logistic Regression)
- Matplotlib, Seaborn – Data visualization
- Jupyter Notebook – Development environment

## 🧠 Problem Statement
Traditional stock prediction models often ignore the role of real-world events (like news). This project aims to bridge market data and real-time sentiment to improve predictive accuracy.

## 📁 Dataset
- `event_driven_stock_prediction_dataset.csv`  
  Includes: `Date`, `Company`, `Headline`, `Label`  
  Labels: `1` for rise, `0` for fall

## 🔄 Workflow
1. Data Preprocessing – cleaned text, removed stopwords
2. Sentiment Scoring – polarity and subjectivity
3. Feature Engineering – encoded variables
4. Model Training – RF, Logistic Regression
5. Evaluation – accuracy, confusion matrix
6. Visualization – sentiment vs movement

## 📊 Results
- Best Accuracy: ~91% (Random Forest)
- Positive news headlines correlate strongly with upward movement

## 🧪 How to Run
```bash
# Clone the repo
git clone https://github.com/Dhruv17204/event-driven-stock-prediction.git
cd event-driven-stock-prediction

# Install dependencies
pip install -r requirements.txt

# Launch notebook
jupyter notebook event_driven_stock_prediction.ipynb
```

## 📦 Requirements
```
pandas  
numpy  
textblob  
scikit-learn  
nltk  
matplotlib  
seaborn
```

## 💡 Future Improvements
- Use live News API
- Integrate with BERT or LSTM
- Deploy with Streamlit or Gradio

## 👨‍💻 Author
**Dhruv Manoj Patil**  
📧 dhruvpatel21724@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/dhruv-patil) | [GitHub](https://github.com/Dhruv17204)
