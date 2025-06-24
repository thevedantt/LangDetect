
# 🌐 Language Detection System

This is a simple yet powerful **language detection model** built using **Python and scikit-learn**. It uses a **Naive Bayes classifier** trained on text samples in various languages. This model can accurately identify the language of any given text input and can be a crucial component in **multilingual bots**, **chat systems**, or **international content platforms**.

> **Note:** This model can only detect the languages mentioned in the dataset.

---

## 🚀 Features

- 🧠 **Text Classification using NLP**  
  Detects the language of the input text using a supervised machine learning approach.

- 🧪 **Trained with CountVectorizer + Naive Bayes**  
  Uses Bag-of-Words for text vectorization and a Multinomial Naive Bayes classifier.

- 📊 **Evaluation Metrics Included**  
  Accuracy, classification report, and confusion matrix are used to evaluate performance.

- ✨ **User Input Supported**  
  Accepts custom text input and predicts the corresponding language.

---

## 🛠️ Tech Stack

- **Python 3**
- **Pandas, NumPy** – Data manipulation
- **Scikit-learn** – Machine learning & evaluation
- **Matplotlib, Seaborn** – Visualization

---

## 📂 Dataset

The dataset used contains multilingual text samples and their corresponding language labels.

📥 Source:  
`https://raw.githubusercontent.com/amankharwal/Website-data/master/dataset.csv`

---

## 🔍 How It Works

1. **Text is vectorized** using `CountVectorizer` (Bag-of-Words).
2. **Data is split** into training and test sets.
3. **Naive Bayes model is trained** on this data.
4. **User input** is transformed using the same vectorizer.
5. **Prediction is returned** for the entered text's language.

---

## 📈 Example Output

```bash
Enter a Text to Detect Language: Bonjour, comment allez-vous?
Predicted Language: French
```

---

## 📌 Use Cases

- 🗨️ Multilingual Chatbots
- 🌍 Language-based Content Recommendation
- 🧭 Auto Language Routing in Customer Support
- 🔐 Language-based Access or Redirection in Web Apps

---

## ✅ Future Improvements

- Upgrade to `TfidfVectorizer` for better feature extraction.
- Add top-N language suggestions with confidence scores.
- Integrate deep learning-based language models for higher accuracy.
- Deploy as a REST API or Web App (e.g., using Streamlit or Flask).

---

## 📦 Installation & Running

```bash
# Install dependencies
pip install pandas numpy scikit-learn matplotlib seaborn

# Run the script
python language_detector.py
```

