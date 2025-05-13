# 🐳 Dockerfile Generator (GenAI-Powered)

A GenAI-powered Python tool that generates optimized Dockerfiles based on user-input programming languages using [Ollama](https://ollama.com) and the `llama3` large language model.

---

## 📦 Features

- 🔧 Generates production-grade Dockerfiles with best practices
- 🤖 Uses `llama3` model locally via Ollama
- 💡 Lightweight CLI-based tool
- 🧠 No internet or OpenAI API required — runs fully offline

---

## 🖥️ Prerequisites

### 1. Install Ollama

- [Download Ollama](https://ollama.com/download) for your OS
- Or install via terminal:

#### For Linux:
```bash
curl -fsSL https://ollama.com/install.sh | sh
For MacOS:
brew install ollama
2. Start Ollama Service
bash
Copy
Edit
ollama serve
3. Pull the Required Model
bash
Copy
Edit
ollama pull llama3



 Project Setup
1. Clone the Repository
bash
Copy
Edit
git clone https://github.com/<your-username>/dockerfile-generator.git
cd dockerfile-generator
2. Create Virtual Environment
Windows:
bash
Copy
Edit
python -m venv venv
.\venv\Scripts\activate
Linux/Mac:
bash
Copy
Edit
python3 -m venv venv
source venv/bin/activate
3. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
🧠 How It Works
Takes a programming language input from the user

Sends a well-crafted prompt to llama3 via Ollama

Receives and displays a clean, production-ready Dockerfile



🛠 Troubleshooting
❗ Make sure ollama serve is running

❗ Ensure the llama3 model is pulled

❗ Use model='llama3' in the script, not llama3.1:8b
