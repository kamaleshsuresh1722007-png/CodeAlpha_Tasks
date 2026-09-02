# 🤖 AI FAQ Chatbot

An intelligent **AI-powered FAQ Chatbot** developed as **Project 2 of the CodeAlpha Artificial Intelligence Internship**.

The chatbot is designed to answer frequently asked questions using a prepared FAQ knowledge base. It uses **Natural Language Processing (NLP)** and **TF-IDF with cosine similarity** to identify the most relevant answer for a user's question.

## 🚀 Features

* 💬 **Interactive Chat Interface** — Users can ask questions through a simple chatbot interface.
* 🧠 **NLP-Based Question Matching** — Processes user questions to identify relevant FAQ entries.
* 🔎 **TF-IDF Vectorization** — Converts FAQ text into numerical representations for similarity analysis.
* 📐 **Cosine Similarity** — Compares the user's question with available FAQs and selects the most relevant match.
* 📚 **FAQ Knowledge Base** — Uses a structured dataset containing frequently asked questions and answers.
* 🗂️ **Category-Based FAQs** — Includes categories such as AI, Machine Learning, Deep Learning, NLP, Python, Data Science, Streamlit & Tools, and General Support.
* ⚡ **Fast Response Generation** — Quickly retrieves the most relevant answer from the FAQ dataset.
* 🖥️ **Streamlit Interface** — Provides a clean and interactive web-based chatbot experience.
* 🧹 **Text Preprocessing** — Uses NLP preprocessing techniques to improve question matching.

## 🛠️ Technologies Used

* **Python**
* **Streamlit**
* **NLTK**
* **Scikit-learn**
* **Pandas**
* **TF-IDF Vectorization**
* **Cosine Similarity**

## 📂 Project Structure

```text
Task2_AI_FAQ_Chatbot/
│
├── app.py
├── preprocess.py
├── requirements.txt
├── README.md
│
└── data/
    └── faq.csv
```

## 📊 FAQ Dataset

The chatbot uses a structured CSV dataset containing frequently asked questions and their corresponding answers.

The dataset covers topics including:

```text
AI
Machine Learning
Deep Learning
Natural Language Processing
Python Programming
Data Science
Streamlit & Tools
General & Support
```

The FAQ dataset provides the knowledge base from which the chatbot retrieves appropriate responses.

## 🧠 How the Chatbot Works

```text
User Question
      │
      ▼
Text Preprocessing
      │
      ▼
TF-IDF Vectorization
      │
      ▼
Cosine Similarity
      │
      ▼
Compare with FAQ Knowledge Base
      │
      ▼
Find Most Relevant Question
      │
      ▼
Return Matching Answer
      │
      ▼
Display Response
```

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/kaushiksrj17-cmyk/CodeAlpha_Tasks.git
```

### 2. Navigate to the project

```bash
cd CodeAlpha_Tasks/Task2_AI_FAQ_Chatbot
```

### 3. Create a virtual environment

```bash
python -m venv .venv
```

### 4. Activate the virtual environment

**Windows PowerShell:**

```powershell
.venv\Scripts\Activate.ps1
```

### 5. Install dependencies

```bash
pip install -r requirements.txt
```

## ▶️ Run the Chatbot

Start the Streamlit application:

```bash
streamlit run app.py
```

The chatbot will open in your web browser.

## 💡 How It Works

1. The user enters a question in the chatbot interface.
2. The input is processed using NLP preprocessing techniques.
3. The FAQ dataset is converted into TF-IDF vectors.
4. The user's question is compared with the FAQ questions using cosine similarity.
5. The system identifies the most relevant FAQ.
6. The corresponding answer is displayed to the user.

## 📌 Example

**User Question:**

```text
What is artificial intelligence?
```

**Chatbot:**

```text
Artificial Intelligence is a field of computer science
that focuses on creating systems capable of performing
tasks that normally require human intelligence.
```

The chatbot selects the answer based on the similarity between the user's question and the questions stored in the FAQ dataset.

## 🔍 NLP Techniques Used

### Text Preprocessing

The project uses **NLTK** for preprocessing operations that help normalize and prepare text for similarity analysis.

These operations can include:

* Tokenization
* Stop-word handling
* Word normalization
* Lemmatization

### TF-IDF

**Term Frequency–Inverse Document Frequency (TF-IDF)** converts text into numerical vectors based on the importance of words within the FAQ collection.

### Cosine Similarity

Cosine similarity measures how closely the user's question matches each FAQ question.

The FAQ with the highest similarity score is selected as the most relevant response.

## 🎯 Project Objective

The objective of this project is to build a practical FAQ chatbot using Natural Language Processing techniques while gaining hands-on experience with:

* NLP
* Text preprocessing
* TF-IDF vectorization
* Cosine similarity
* Dataset handling
* Python programming
* Streamlit application development
* Conversational AI concepts

## 🔮 Future Enhancements

Possible improvements include:

* 🤖 Integration with Large Language Models
* 💾 Persistent conversation history
* 🎤 Voice-based questions
* 🌐 Multi-language FAQ support
* 📊 Chatbot analytics dashboard
* 🔄 Automatic FAQ dataset updates
* 🔐 User authentication
* ☁️ Cloud deployment
* 🧠 Semantic embeddings using transformer models

## 👨‍💻 Internship Information

**Program:** CodeAlpha Artificial Intelligence Internship
**Project:** Project 2 — AI FAQ Chatbot
**Developer:** S. Kaushik

## 📜 License

This project was developed for educational and internship purposes as part of the CodeAlpha Artificial Intelligence Internship.
