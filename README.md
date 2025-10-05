# ⭐ The AI Assistant & Command Generator CLI 🚀
### A Developer's Essential Productivity Tool  

This is an interactive **Command-Line Interface (CLI)** assistant built with **Python** and the **Google Gemini API**.  
It’s designed to **boost developer productivity** by providing instant AI assistance and a **secure, persistent vault** for your most complex shell commands.

---

## 🔥 Key Features at a Glance

| **Category**        | **Feature Highlights** |
|----------------------|-------------------------|
| **Secure Setup**     | API Key loaded securely via the `.env` file (never hardcoded). |
| **AI Generation**    | Instant code snippets, command line recipes, and complex explanations from Gemini. |
| **Multimodal Canvas**| Analyzes content from Images, PDFs, DOCX, and Archives for summarization. |
| **Productivity Vault** | Persistent storage for your complex shell commands (recipes) that can be searched and copied instantly. |
| **Export to Sheets** | (Optional) Export and manage your saved commands for external usage. |

---

## ✨ Core Functionality Breakdown

### 🧠 1. AI Analysis & Generation Tools  
These features leverage the **Gemini model** for powerful developer assistance:

#### 🗣️ General Q&A (Web Search)
- Uses **Google Search grounding** for factual accuracy with citation sources.  

#### 💻 Explain Code Snippet  
- Paste any code block (Python, Bash, etc.) and receive a **plain-language breakdown** of its logic.  

#### 💡 Code Generator  
- Describe a coding task (e.g., *“Write a Python script for file hashing”*).  
- Receive the **complete, runnable code** in Markdown format.  

#### 📝 Summarize Local File  
- Provides a summary of complex local files, including **images** (analyzing diagrams/screenshots) and **documents**.  

---

### 📚 2. Command Vault (Recipe Management)
A persistent solution for managing complex terminal commands in a local **JSON vault**.

#### 🛠️ AI Generate New Command  
- Describe a terminal task (e.g., *“delete all old docker images”*).  
- The AI returns the **accurate, optimized shell command string**.  

#### ➕ Add Known Command Recipe  
- Manually save **custom, complex commands** and tag them for quick retrieval.  

#### 🔍 Search & View Recipe  
- Quickly search your vault by **name or tag** to retrieve and copy the full command.  

---

## 🛠️ Setup & Installation

### ✅ Prerequisites
- **Python 3.x**  
- **Google Gemini API Key** (Get one from [Google AI Studio](https://makersuite.google.com/app/apikey))

---

### 📦 Installation Steps

#### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Kashish-2005/AI-Assistant-Command-Generator-CLI
cd AI-Assistant-Command-Generator-CLI

2️⃣ Install Dependencies

You must install the primary libraries, including the python-dotenv library for secure key management:

pip install python-dotenv PyMuPDF python-docx openpyxl python-pptx Pillow requests

🔒 API Key Configuration (The Secure Method)

Your Gemini API key is loaded from the environment variable GEMINI_API_KEY.

Create a file named .env in the root directory of your project.

Add your Gemini API key inside this file in the following format:

# .env file content
GEMINI_API_KEY='YOUR_KEY_HERE'


✅ The Python script automatically loads this file when it starts — your API key stays safe and unexposed.

▶️ How to Run the Assistant

Launch the application from your terminal:

python cli.py


Or, if you installed the package via:

pip install -e .


You can use the shortcut:

ai-cli

💬 Contributing

Feel free to fork this repository, open issues, and submit pull requests to improve the CLI or extend its AI features.

📜 License

This project is licensed under the MIT License — you’re free to use, modify, and distribute it with attribution.

🧑‍💻 Developed By

Kashish
Ruchira



