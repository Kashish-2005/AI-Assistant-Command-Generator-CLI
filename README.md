🤖 AI Assistant & Command Generator CLI
A powerful, menu-driven command-line interface (CLI) built with Python that combines general knowledge access with a personal command vault and on-demand command generation. It uses the Google Gemini API to handle complex tasks like research, code explanation, and generating executable shell commands.

✨ Features at a Glance
This assistant provides six core functions split between AI analysis and developer utility. Note the dual power of dynamic command generation and static command saving.

🛠️ Command Generation & Vault (Core Utility)
🧠 AI Generate New Command: Describe a complex terminal task in plain English (e.g., "resize all images to 800px"), and the AI instantly generates the executable command for you. This is perfect for commands you've never used before!

➕ Add New Command Recipe (Manual): Save your own complex, hard-to-remember shell commands for later use.

🔍 Search & View Recipe: Find saved commands by name or tag and instantly view the full command string for easy copy/paste.

🧠 AI Analysis Tools
🗣️ General Q&A (Web Search): Ask any question and get an answer grounded in up-to-date information using Google Search.

💻 Explain Code Snippet: Paste any piece of code (Python, JavaScript, Bash, etc.) and get a clear, simple explanation of what it does.

📝 Summarize Local File: Quickly summarize the content of any text file (e.g., meeting notes or a long log file).

🚀 Setup & Installation
To run this project, you need Python and the requests library.

1. Dependencies
Open your terminal and install the required library:

pip install requests

2. API Key Setup (Crucial for Security!)
This project does not hardcode your API key. You must set your Gemini API Key as an environment variable before running the script.

Get Your Key: Obtain a GEMINI_API_KEY from Google AI Studio.

Set the Variable: Run the appropriate command for your operating system in your terminal:

OS / Shell

Command (Replace YOUR_KEY_HERE)

macOS/Linux (Bash/Zsh)

export GEMINI_API_KEY='YOUR_KEY_HERE'

Windows (PowerShell)

$env:GEMINI_API_KEY='YOUR_KEY_HERE'

3. Run the Assistant
Save the project file as ai_assistant_cli.py and run it:

python ai_assistant_cli.py

💡 How to Use
The application is entirely menu-driven. Just enter the corresponding number for the task you want to perform.

Example: Command Generation (Option 4) - Solving a New Problem
To instantly create a complex command for a problem you haven't solved yet:

Select 4 (AI Generate New Command).

Input your request: Find all text files modified in the last week and print their names.

The AI will return the command (e.g., find . -type f -name "*.txt" -mtime -7 -print).

You can then choose to save (y) this command to your local Recipe Book for permanent storage.

Example: Searching Your Vault (Option 6) - Reusing a Solution
To quickly retrieve a saved command from your local vault:

Select 6 (Search & View Recipe).

Input a tag or keyword: grep

Select the recipe number you want, and the full command will be printed cleanly, ready to be copied and pasted into your working shell.# AI-Assistant-Command-Generator-CLI
