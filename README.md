⭐ The AI Assistant & Command Generator CLI 🚀
A Developer's Essential Tool

This is an interactive Command-Line Interface (CLI) assistant built with Python and the Google Gemini API. It's designed to boost developer productivity by combining powerful AI features with a secure, persistent vault for your most complex shell commands.

🔥 Features At a Glance
This project is ideal for demonstrating:

✅ Advanced API Integration – Seamless, stable communication with a powerful AI model.

✅ Multimodal AI – Processing, understanding, and summarizing image content (like flowcharts or diagrams).

✅ Local Data Persistence – Custom commands saved in a JSON-based local command vault.

✨ Core Functionality Breakdown
🧠 1. AI Analysis & Generation Tools
These features leverage the powerful Gemini model for deep analysis, smart generation, and creative assistance, fully embracing the "vibe coding" philosophy:

🗣️ General Q&A (Web Search)

Ask anything! Uses Google Search grounding for factual accuracy with citation sources.

💻 Explain Code Snippet

Paste any code (Python, JS, Shell, etc.).

Get a plain-language breakdown of its logic, inputs, and outputs.

💡 Code Generator

Describe a coding task (e.g., "Write a Python script for file hashing").

The assistant returns complete, runnable code in Markdown format.

📝 Summarize Local File (Multi-Format Support)

Provides Gemini's assistance to extract meaning from complex data sources.

📚 2. Command Vault (Productivity & Reusability)
A persistent, powerful solution for managing complex and reusable terminal commands.

🛠️ AI Generate New Command

Describe any terminal task in plain English.

The AI instantly returns an accurate shell command (e.g., find, xargs, etc.).

➕ Add New Command Recipe

Manually save custom, complex commands (e.g., ffmpeg, curl, rsync).

Tag them with names and labels for quick retrieval.

🔍 Search & View Recipe

Search your command vault by name or tag.

Instantly retrieve and copy the full command string.

🖼️ Supported File Types in the Canvas
The Summarize Local File feature uses robust reading mechanisms and Gemini's Vision capabilities to process various file formats:

Category	File Extensions	Gemini's Role / Developer Value
Multimodal Vision	.jpg, .jpeg, .png, etc.	The assistant analyzes images, extracts text from diagrams or screenshots, and describes the visual content—essential for understanding flowcharts or code snippets saved as pictures.
Primary Documents	.pdf, .docx, .xlsx, .pptx	Extracts text from dense, structured documents for concise summarization.
Code & Archives	.zip, .tar, .py, .md	Analyzes archive structure and file listings to infer project purpose without unpacking.

Export to Sheets
🛠️ Setup & Installation
✅ Prerequisites
Python 3.x

Google Gemini API Key (Get one from Google AI Studio)

📦 Installation Steps
Clone the Repository

Bash

git clone [(https://github.com/Kashish-2005/AI-Assistant-Command-Generator-CLI)]
cd AI-Assistant-Command-Generator-CLI
Install Dependencies
(The script attempts to install these automatically, but running this ensures all are present:)

Bash

pip install PyMuPDF python-docx openpyxl python-pptx Pillow requests
🔒 API Key Configuration
Your Gemini API key should never be hardcoded or committed to GitHub.

Set the GEMINI_API_KEY environment variable:

Operating System	Command
macOS / Linux	export GEMINI_API_KEY='YOUR_KEY_HERE'
Windows (CMD)	set GEMINI_API_KEY='YOUR_KEY_HERE'
Windows (PowerShell)	$env:GEMINI_API_KEY='YOUR_KEY_HERE'

Export to Sheets
▶️ How to Run the Assistant
Once the dependencies and API key are configured, launch the assistant:

Bash

python ai_assistant_cli.py
You'll be presented with an interactive menu to access all core features!
