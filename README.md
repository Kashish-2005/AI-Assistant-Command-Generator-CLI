# 🚀⭐ The AI Assistant & Command Generator CLI ⭐🚀  
### 🤖 A Developer's Essential Tool

This is an interactive **Command-Line Interface (CLI)** assistant built with **Python** and the **Google Gemini API**. It’s designed to **boost developer productivity** by combining powerful AI features with a **secure, persistent vault** for your most complex shell commands.

---

## 🔥 Features At a Glance

This project is ideal for demonstrating:

- ✅ **API Integration** – Seamless, secure communication with a powerful AI model.
- ✅ **Secure Configuration** – API key management using environment variables (no hardcoding!).
- ✅ **Local Data Persistence** – Custom commands saved in a JSON-based local command vault.

---

## ✨ Core Functionality Breakdown

### 🧠 1. AI Analysis & Generation Tools

These features leverage Gemini AI for deep analysis, smart generation, and creative code help:

#### 1. 🗣️ General Q&A (Web Search)
- Ask anything!
- Uses Google Search grounding for **factual accuracy** with citation sources.

#### 2. 💻 Explain Code Snippet
- Paste any code (Python, JS, Shell, etc.)
- Get a **plain-language breakdown** of its logic, inputs, and outputs.

#### 3. 💡 Code Generator
- Describe a coding task (e.g., “Write a Python script for file hashing”)
- The assistant returns **complete, runnable code** in Markdown format.

#### 4. 📝 Summarize Local File
- Provide a path to a local `.txt` file.
- The assistant will return a **concise, bulleted summary**.

---

### 📚 2. Command Vault (Productivity & Reusability)

A powerful solution for managing complex and reusable terminal commands.

#### 5. 🛠️ AI Generate New Command
- Describe any terminal task in plain English.
- The AI instantly returns an **accurate shell command** (e.g., `find`, `xargs`, etc.).

#### 6. ➕ Add New Command Recipe
- Manually save custom, complex commands (e.g., `ffmpeg`, `curl`, `rsync`).
- Tag them with names and labels for quick retrieval.

#### 7. 🔍 Search & View Recipe
- Search your command vault by name or tag.
- Instantly retrieve and copy the **full command string**.

---

## 🛠️ Setup & Installation

### ✅ Prerequisites

- Python 3.x
- Google Gemini API Key (Get one from [Google AI Studio](https://aistudio.google.com/app/apikey))

---

### 📦 Installation Steps

**1. Clone the Repository**
    - git clone [[(https://github.com/Kashish-2005/AI-Assistant-Command-Generator-CLI)]
     cd ai-assistant-cli

**2. Install Dependencies**
    - pip install requests

### 🔒 API Key Configuration

- Your Gemini API key should never be hardcoded. Use environment variables.
## macOS / Linux (Bash/Zsh)
- export GEMINI_API_KEY='YOUR_KEY_HERE'

## Windows (PowerShell)
- $env:GEMINI_API_KEY='YOUR_KEY_HERE'

---

### ▶️ How to Run the Assistant

- Once the API key is configured, launch the assistant via:
- python ai_assistant_cli.py

- you'll be presented with an interactive menu to access all seven core features!
  ---
