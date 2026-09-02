# 🌐 AI Language Translator

An interactive **AI-powered Language Translator** developed as **Project 1 of the CodeAlpha Artificial Intelligence Internship**.

The application provides a simple and user-friendly interface for translating text between multiple languages, with additional features such as automatic language detection, text-to-speech, translation history, favorites, language swapping, and dark mode.

## 🚀 Features

* 🌍 **Multi-Language Translation** — Translate text between multiple supported languages.
* 🔍 **Automatic Language Detection** — Automatically detects the source language when enabled.
* 🔄 **Swap Languages** — Quickly switch the source and target languages.
* 🔊 **Text-to-Speech** — Listen to translated text using speech synthesis.
* 📋 **Copy Translation** — Easily copy translated text.
* 📥 **Download Translation** — Download translations as a text file.
* 🕘 **Translation History** — Keep track of previous translations.
* ⭐ **Favorite Translations** — Save important translations for quick access.
* 📊 **Character & Word Count** — Displays text statistics.
* 🌙 **Dark Mode** — Provides a comfortable interface for different viewing preferences.
* 🧹 **Clear Text** — Quickly clear the input and translation fields.

## 🛠️ Technologies Used

* **Python**
* **Streamlit**
* **Deep Translator**
* **Google Translator**
* **gTTS (Google Text-to-Speech)**
* **Pyperclip**

## 📂 Project Structure

```text
Task1_Language_Translator/
│
├── app.py
├── requirements.txt
└── README.md
```

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/kaushiksrj17-cmyk/CodeAlpha_Tasks.git
```

### 2. Navigate to the project

```bash
cd CodeAlpha_Tasks/Task1_Language_Translator
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

## ▶️ Run the Application

Start the Streamlit application with:

```bash
streamlit run app.py
```

The application will open in your web browser.

## 💡 How It Works

```text
User Input
    │
    ▼
Language Selection / Auto Detection
    │
    ▼
Translation Engine
    │
    ▼
Translated Text
    │
    ├── Text-to-Speech
    ├── Copy
    ├── Download
    ├── Favorite
    └── Translation History
```

## 🖥️ Application Workflow

1. Enter the text that needs to be translated.
2. Select the source language or enable automatic detection.
3. Select the target language.
4. Click the **Translate** button.
5. View the translated result.
6. Use additional features such as text-to-speech, copy, download, history, and favorites.
7. Swap the languages when required.

## 📌 Example

**Input:**

```text
Hello, welcome to my AI project!
```

**Source Language:**

```text
English
```

**Target Language:**

```text
Tamil
```

The application processes the input and displays the translated result.

## 🎯 Project Objective

The objective of this project is to develop a practical and interactive AI-based translation application while gaining hands-on experience with:

* Python application development
* Streamlit web application development
* Translation APIs/libraries
* Natural language processing concepts
* Text-to-speech integration
* User interface design
* Git and GitHub project management

## 🔮 Future Enhancements

Possible future improvements include:

* Voice input for translation
* Real-time speech translation
* Offline translation support
* More advanced translation models
* Mobile application support
* Translation API optimization
* User accounts and cloud-based history
* Additional language support

## 👨‍💻 Internship Information

**Program:** CodeAlpha Artificial Intelligence Internship
**Project:** Project 1 — AI Language Translator
**Developer:** S. Kaushik

## 📜 License

This project was developed for educational and internship purposes as part of the CodeAlpha Artificial Intelligence Internship.
