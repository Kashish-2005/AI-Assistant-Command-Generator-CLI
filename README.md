# 🚀 AI Assistant & Command Generator CLI  
*A Powerful Developer Companion built with Python & Gemini API*

![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python)  
![Gemini](https://img.shields.io/badge/Gemini%20API-Enabled-blueviolet?logo=google)  
![Hackathon Ready](https://img.shields.io/badge/Hackathon-Ready-green?style=flat-square)

---

## ✨ Core Value Proposition

This CLI tool supercharges developer productivity by combining:

- 🧠 **AI-powered command & code generation**
- 📂 **Local vault for storing and retrieving complex shell recipes**
- 💻 **Code explanation, file summarization, and AI Q&A — right from the terminal**

It’s perfect for developers who want fast, intelligent assistance **without leaving the CLI**.

---

## ⚙️ Features & Options

### 🔍 AI Analysis & Generation

| Option | Description |
|--------|-------------|
| **1️⃣ General Q&A** | Ask any question. The AI fetches up-to-date, web-grounded answers. |
| **2️⃣ Explain Code Snippet** | Paste a code block — the AI explains its logic, line by line. |
| **3️⃣ Code Generator** | Describe the code you need (e.g., “Python quicksort script”), and get a runnable version. |
| **4️⃣ Summarize Local File** | Analyze PDFs, docs, images, or zip archives and get bullet-point summaries. |

---

### 🛠 Command Recipe Vault

A local vault to manage and understand your shell command history.

| Option | Description |
|--------|-------------|
| **5️⃣ Generate New Recipe (AI)** | Describe a task (e.g., “clean old Docker images”) — get the shell command instantly. |
| **6️⃣ Add Known Recipe (Manual)** | Manually store your own complex commands with tags and descriptions. |
| **7️⃣ Search & View Recipe** | Quickly look up saved commands by name or tag for reuse. |
| **8️⃣ Explain Recipe (AI)** | Pick any saved command and let the AI explain it in plain English. |

---

## 📦 Setup & Installation

### 🔧 Prerequisites

- ✅ **Python**: Version 3.8 or higher  
- 🔐 **Gemini API Key**: Get yours from [Google AI Studio](https://aistudio.google.com/app/apikey)

---

### 🔐 Environment Variable Setup

Before running the script, set the `GEMINI_API_KEY` in your environment.

#### 💻 For macOS / Linux (Bash or Zsh):

- export GEMINI_API_KEY='YOUR_KEY_HERE'

### Windows (PowerShell)
- $env:GEMINI_API_KEY='YOUR_KEY_HERE'

---

## 📥 Installation Steps

- Clone the repo (or download the files)
- Install base dependencies:
     - pip install requests
- Run the CLI:
     - python ai_assistant_cli.py
-- ✅ Remaining dependencies (for file handling, etc.) will install automatically on first run.

-- you'll be presented with an interactive menu to access all seven core features!
  ---
