🚀⭐ AI Assistant & Command Generator CLI ⭐🚀
An interactive Command-Line Interface (CLI) assistant built with Python and the Google Gemini API. This project combines powerful AI analysis with a persistent local vault for your complex shell commands, making it a must-have developer utility.

It's an ideal project for showcasing API integration, secure environment variable usage, and local file persistence (JSON).

✨ Key Features Overview
The CLI organizes its utility into two core, high-impact sections: AI Analysis and the Command Vault.

🧠 1. AI Analysis Tools (Powered by Gemini)
Menu Option

Feature

Description

1

🗣️ General Q&A

Ask any general knowledge question. Uses Google Search Grounding to ensure answers are based on up-to-date, verifiable information from the web.

2

💻 Explain Code Snippet

Paste any code (Python, JavaScript, etc.) and get a clean, detailed explanation of its purpose, logic, and outputs.

3

💡 Code Generator

Ask for a piece of code (e.g., "Python function for binary search") and the AI will generate and return the complete, runnable code block.

4

📝 Summarize Local File

Provide the path to any text file (notes, documentation, logs) and the AI will read it and return a concise, bulleted summary.

📚 2. Command Vault (Productivity & Reusability)
Menu Option

Feature

Description

5

🛠️ AI Generate New Command

Describe a complex task in plain English (e.g., "Find all files older than 30 days and zip them"). The AI instantly generates the exact shell command (find, xargs, etc.).

6

➕ Add New Command Recipe

Manually save your own complex, hard-to-remember shell commands (e.g., long ffmpeg strings) with tags for easy future retrieval.

7

🔍 Search & View Recipe

Search your local vault by name or tag. The tool displays the full command string, ready for you to copy and paste directly into your terminal.

🛠️ Setup and Installation
Prerequisites
Python 3.x

Gemini API Key: Get a key from Google AI Studio.

Installation Steps
Clone the Repository:

git clone [https://github.com/YourUsername/ai-assistant-cli.git](https://github.com/YourUsername/ai-assistant-cli.git)
cd ai-assistant-cli

Install Requirements:

pip install requests

🔒 API Key Configuration (CRITICAL STEP)
For security and best practice, the application requires you to set the API key as an environment variable.

DO NOT paste your API key directly into the Python file.

Use the command appropriate for your system, replacing YOUR_KEY_HERE with your actual Gemini API key:

Operating System

Command

macOS / Linux (Bash/Zsh)

export GEMINI_API_KEY='YOUR_KEY_HERE'

Windows (PowerShell)

$env:GEMINI_API_KEY='YOUR_KEY_HERE'

▶️ How to Run the Assistant
After successfully setting your environment variable, run the application from your terminal:

python ai_assistant_cli.py

The interactive menu will immediately appear, allowing you to choose any of the available functions.
