# 🧠 StudyBuddy AI

> Transform your PDF notes into quizzes, flashcards, and summaries — instantly, using AI.

![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=flat&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-LLaMA_3-orange?style=flat)
![License](https://img.shields.io/badge/License-MIT-green?style=flat)

---

## ✨ Features

- ⚡ **Smart Quizzes** — Generate MCQ or True/False questions with difficulty control and instant answer explanations
- 🃏 **Flashcards** — Flip through AI-generated study cards, shuffle them, or view all at once
- 📋 **AI Summary** — Get a clean, structured overview of your entire document in seconds
- 🎯 **Score Tracker** — Real-time progress bar, per-question feedback, and a final grade
- ⚙️ **Customisable** — Choose number of questions, difficulty (Easy / Medium / Hard), and question type

---

## 🖥️ Demo

Upload a PDF → click **Generate Quiz**, **Make Flashcards**, or **Summarise Notes** → study smarter.

---

## 🚀 Getting Started

### 1. Clone the repo

```bash
git clone https://github.com/your-username/studybuddy-ai.git
cd studybuddy-ai
```

### 2. Create a virtual environment (recommended)

```bash
python -m venv .venv

# Windows
.venv\Scripts\activate

# Mac/Linux
source .venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Set your Groq API key

Get a free key at [console.groq.com](https://console.groq.com)

**Windows (PowerShell):**
```powershell
$env:GROQ_API_KEY="your_api_key_here"
```

**Mac/Linux:**
```bash
export GROQ_API_KEY="your_api_key_here"
```

### 5. Run the app

```bash
python -m streamlit run study_buddy.py
```

Open [http://localhost:8501](http://localhost:8501) in your browser.

---

## 📦 Requirements

```
streamlit
groq
PyPDF2
```

Or install via:
```bash
pip install streamlit groq PyPDF2
```

---

## 🗂️ Project Structure

```
studybuddy-ai/
├── study_buddy.py      # Main Streamlit app
├── requirements.txt    # Python dependencies
└── README.md           # You're reading it
```

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| [Streamlit](https://streamlit.io) | Web UI framework |
| [Groq](https://groq.com) | Ultra-fast LLM inference |
| [LLaMA 3.3 70B](https://groq.com) | Language model for generation |
| [PyPDF2](https://pypdf2.readthedocs.io) | PDF text extraction |

---

## 📄 License

MIT License — feel free to use, modify, and distribute.

---

## 🙌 Contributing

Pull requests are welcome! If you find a bug or have a feature idea, open an issue.

---

<div align="center">
  Made with ❤️ using Groq + Streamlit
</div>
