# 🚀 AI Assistant & Command Generator CLI  

A powerful **menu-driven Python Command Line Interface (CLI)** designed to enhance developer productivity and streamline technical documentation.  
It combines the intelligence of the **Gemini API** for analysis and code generation with a robust local **📚 Recipe Vault** for storing essential shell commands.  

---

## ✨ Key Features & Benefits  
- ⚡ **Zero-Setup Demo** → Works on Windows, macOS, or Linux using simple environment variables.  
- 🧠 **Intelligent Assistance** → Real-time web search, code explanations, and file summarization.  
- 🛠️ **Developer Productivity** → Automates creation and explanation of complex Linux/CLI commands.  

---

## 🛠️ Project Setup (Windows/VS Code Optimized)  

### 1️⃣ API Key Configuration (Crucial!)  
You must obtain a Gemini API Key from **Google AI Studio** and set it as an environment variable named `GEMINI_API_KEY`.  

💻 **Setting the Environment Variable:**  
Run the command corresponding to your operating system **before** running the Python script.  

| Operating System | Command |
|------------------|---------|
| 🪟 Windows PowerShell / VS Code | ```powershell $env:GEMINI_API_KEY='YOUR_KEY_HERE' ``` |
| 🍎 macOS / 🐧 Linux (Bash/Zsh) | ```bash export GEMINI_API_KEY='YOUR_KEY_HERE' ``` |

> 🔑 Replace `YOUR_KEY_HERE` with your actual API key. The quotes are important!  

---

### 2️⃣ Install Dependencies  
- Install all required packages for AI communication and file handling:  
   - pip install requests PyMuPDF python-docx openpyxl python-pptx Pillow

### 3️⃣ Run the Assistant
- Execute the script directly from your terminal:
   - python ai_assistant_cli.py

---

## 💡 AI Analysis & Generation Features
- The core functionality of the assistant is powered by the Gemini API:

   - 🗣 General Q&A (Web Search) → Get up-to-date, grounded answers with Google Search integration.
    
   - 💻 Explain Code Snippet → Paste any code block and get a simple, clear explanation of its purpose and logic.
    
   - 💡 Code Generator (NEW!) → Generate runnable scripts/functions (e.g., Python script for file hashing).
    
   - 📝 Summarize Local File → Summarizes text from TXT, MD, PDF, DOCX, XLSX, and Images.

---

## 📚 Command Recipe Vault (Persistence)
- Easily save and recall CLI commands with local persistence in command_recipes.json:

   - 🛠 Generate New Recipe (AI) → Describe a command, and AI generates & saves it.
    
   - ➕ Add Known Recipe (Manual) → Save a command you already know with tags & names.
    
   - 🔍 Search & View Recipe → Find commands by name or tag, ready for instant copy/paste.
    
   - 🧠 Explain Recipe (AI) → Get detailed explanations of flags, pipes, and syntax.

---

