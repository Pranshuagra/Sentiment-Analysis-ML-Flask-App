# 😊 Sentiment Analysis ML Flask App

A Machine Learning-based Sentiment Analysis web application built using Python, Flask, NLTK, and VADER Sentiment. The application analyzes textual input and identifies the sentiment expressed in the text.

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.12-blue?logo=python" />
  <img src="https://img.shields.io/badge/Flask-Web%20Framework-black?logo=flask" />
  <img src="https://img.shields.io/badge/ML-Sentiment%20Analysis-orange" />
  <img src="https://img.shields.io/badge/Deployment-Render-46E3B7?logo=render" />
  <img src="https://img.shields.io/badge/Status-Live-success" />
</p>

## 🌐 Live Demo

**Try the application here:**

🔗 https://sentiment-analysis-ml-flask-app-89r1.onrender.com/

## 📌 Project Overview

Sentiment Analysis is a Natural Language Processing (NLP) technique used to identify and understand the emotional tone of text.

This project uses VADER (Valence Aware Dictionary and sEntiment Reasoner) to analyze textual data and determine whether the expressed sentiment is positive, negative, or neutral.

The application provides a simple web interface where users can enter text and analyze its sentiment.

## ✨ Features

- **Text Sentiment Analysis:** Analyze user-provided text.
- **Positive Sentiment Detection:** Identify positive opinions and expressions.
- **Negative Sentiment Detection:** Identify negative opinions and expressions.
- **Neutral Sentiment Detection:** Identify neutral statements.
- **VADER Sentiment Analyzer:** Perform lexicon-based sentiment analysis.
- **Flask Web Application:** Simple web-based interface.
- **Live Deployment:** Hosted on Render.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Programming Language |
| Flask | Web Framework |
| NLTK | Natural Language Processing |
| VADER Sentiment | Sentiment Classification |
| Scikit-learn | Machine Learning Library |
| HTML/CSS | Frontend |
| Gunicorn | Production WSGI Server |
| Render | Cloud Deployment |

## 📂 Project Structure

```text
Sentiment-Analysis-ML-Flask-App/
│
├── app.py
├── requirements.txt
├── .python-version
├── .gitignore
│
├── templates/
│   └── index.html
│
├── static/
│   ├── css/
│   ├── js/
│   └── images/
│
└── README.md
```

*Note: Adjust the structure above to match the actual folders and files in your repository.*

## ⚙️ Installation & Setup

Follow these steps to run the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/Pranshuagra/Sentiment-Analysis-ML-Flask-App.git
```

### 2. Navigate to Project Directory

```bash
cd Sentiment-Analysis-ML-Flask-App
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

Activate the environment:

**Windows:**

```bash
venv\Scripts\activate
```

**Linux / macOS:**

```bash
source venv/bin/activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Run the Application

```bash
python app.py
```

### 6. Open in Browser

Visit:

```text
http://127.0.0.1:5000/
```

## 🧠 How Sentiment Analysis Works

The application uses VADER Sentiment Analysis to evaluate the emotional tone of text.

The sentiment analyzer calculates four important scores:

- **Positive Score:** Measures positive sentiment.
- **Negative Score:** Measures negative sentiment.
- **Neutral Score:** Measures neutral sentiment.
- **Compound Score:** Provides an overall normalized sentiment score between -1 and +1.

The compound score can help interpret the overall sentiment:

| Compound Score | Sentiment |
|---|---|
| >= 0.05 | Positive |
| <= -0.05 | Negative |
| Between -0.05 and 0.05 | Neutral |

## 💡 Example Inputs

**Positive Text:**

```text
I absolutely love this product!
It is amazing and works perfectly.
```

**Negative Text:**

```text
This product is terrible.
I am extremely disappointed.
```

**Neutral Text:**

```text
The product was delivered today.
```

## 🚀 Deployment

This application is deployed using Render.

**Live Application:**

https://sentiment-analysis-ml-flask-app-89r1.onrender.com/

Deployment configuration:

- Platform: Render
- Framework: Flask
- Python Version: 3.12.11
- Production Server: Gunicorn

## 🔮 Future Improvements

- Integrate advanced Machine Learning and Deep Learning models.
- Add sentiment analysis visualizations and interactive dashboards.
- Support multilingual sentiment analysis.
- Analyze large text datasets.
- Add sentiment analysis for customer reviews and social media data.
- Improve user experience with a modern responsive interface.

## 👨‍💻 Author

**Pranshu Agrahari**

AI/ML & Data Science Enthusiast

- GitHub: https://github.com/Pranshuagra
- Project Repository: https://github.com/Pranshuagra/Sentiment-Analysis-ML-Flask-App

## ⭐ Support

If you find this project useful, consider giving it a ⭐ on GitHub!

---

<p align="center">
  **Built with ❤️ using Python, NLP & Flask**
</p>
