
# 🌐 Language Detection using Machine Learning

A supervised machine learning project that predicts the **language** of a given text using a **Multinomial Naive Bayes classifier** and **Bag-of-Words** feature extraction.
This project demonstrates essential ML concepts such as preprocessing, vectorization, model training, evaluation, and real-time prediction.

---

## ✨ Key Features

* 🔤 Detects the language of any text input
* 🧠 ML pipeline using **CountVectorizer + Naive Bayes**
* 📊 Train–test evaluation with accuracy score
* ⚡ Fast predictions
* 🗂 Clean and easy-to-understand code
* 🧪 Real-time user input detection
* 📁 Fully customizable dataset (`language.csv`)

---

## 📁 Project Structure

```
📦 Language-Detection-ML
│
├── language.csv          # Dataset containing text and its language label
├── language_model.py     # Main machine learning script
└── README.md             # Project documentation
```

---

## 🧠 How It Works

1. Load dataset with Pandas
2. Extract **Text** (input) and **language** (label)
3. Convert text to numerical features using **CountVectorizer**
4. Split data into training & testing sets
5. Train a **Multinomial Naive Bayes** classifier
6. Evaluate accuracy
7. Predict the language of user-provided text

---

## 🛠️ Technologies Used

| Tool / Library      | Purpose                       |
| ------------------- | ----------------------------- |
| **Python**          | Programming language          |
| **NumPy**           | Array handling                |
| **Pandas**          | Data processing               |
| **Scikit-Learn**    | ML algorithms & vectorization |
| **CountVectorizer** | Text → Numerical features     |
| **MultinomialNB**   | Naive Bayes classifier        |

---

## 📦 Installation

Install the required dependencies:

```bash
pip install numpy pandas scikit-learn
```

---

## ▶️ Running the Project

Run the script using:

```bash
python language_model.py
```

Sample interaction:

```
Enter a text: Hola amigo
Predicted language: Spanish
```

---

## 📈 Model Performance

The code prints model accuracy automatically:

```
Test accuracy: 0.95   
```

Accuracy depends on:

* Size of dataset
* Balance between classes
* Number of languages
* Quality of text samples

---

## 🗂 Dataset Format

Your dataset must contain two columns:

| Text                | language |
| ------------------- | -------- |
| Hello, how are you? | English  |
| Bonjour mon ami     | French   |
| Hola amigo          | Spanish  |

You can expand the dataset with more languages and more samples.

---

## 🚀 Future Enhancements

* Switch to **TF-IDF Vectorizer**
* Support more languages
* Add **Streamlit web UI**
* Add **Tkinter desktop application**
* Save & load model using `pickle`
* Add confusion matrix & classification report

---

## 🤝 Contributing

Contributions, improvements, and suggestions are welcome!
Feel free to open issues or submit pull requests.

---

## 📜 License

This project is released under the **MIT License**.

