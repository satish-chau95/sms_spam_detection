# 📩 SMS Spam Detection

A web-based application that classifies SMS messages as **Spam** or **Not Spam** using Natural Language Processing (NLP) techniques and a machine learning model.

🔗 **Live Demo**: [sms-spam-detection-gbq8.onrender.com](https://sms-spam-detection-gbq8.onrender.com)

---

## 🧠 Project Overview

This project leverages NLP for text preprocessing and a machine learning model to predict whether an SMS message is spam. The application is built using Flask for the web interface and includes the following features:

* Text preprocessing (lowercasing, tokenization, stopword removal, stemming)
* Vectorization using a pre-trained vectorizer
* Prediction using a trained classification model
* User-friendly web interface for input and results

---

## 🗂️ Project Structure

```
sms_spam_detection/
├── app.py
├── download_nltk.py
├── model.pkl
├── vectorizer.pkl
├── requirements.txt
├── spam.csv
├── templates/
│   └── index.html
├── nltk_data/
├── Scripts/
├── .gitignore
└── README.md
```

* **app.py**: Main Flask application file.
* **download\_nltk.py**: Script to download necessary NLTK data.
* **model.pkl**: Serialized machine learning model.
* **vectorizer.pkl**: Serialized vectorizer for text data.
* **requirements.txt**: List of Python dependencies.
* **spam.csv**: Dataset used for training the model.
* **templates/index.html**: HTML template for the web interface.
* **nltk\_data/**: Directory containing NLTK data files.([Wikipedia][1])

---

## 🚀 Getting Started

### Prerequisites

* Python 3.6 or higher
* pip (Python package installer)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/satish-chau95/sms_spam_detection.git
   cd sms_spam_detection
   ```



2. **Create a virtual environment (optional but recommended):**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```



3. **Install the required packages:**

   ```bash
   pip install -r requirements.txt
   ```



4. **Download NLTK data:**

   ```bash
   python download_nltk.py
   ```



### Running the Application

```bash
python app.py
```

made with ❤️ by Satish
