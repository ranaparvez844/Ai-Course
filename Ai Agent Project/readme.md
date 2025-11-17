# ✨ Gemini AI Terminal Assistant

A simple and interactive **command-line AI assistant** powered by **Google Gemini 2.5 Flash**.  
This project enables users to chat with an AI model directly from the terminal, featuring a typing animation effect, a basic bad-word filter, retry logic for rate limits, and persistent conversation history.

---

## 📌 Features

- 🤖 **AI chatbot** powered by *Gemini 2.5 Flash*
- 🧠 **Maintains conversation history** throughout the session
- ⛔ **Basic bad-word detection** and filtering
- ⏳ **Natural typing animation** for responses
- 🔁 **Automatic retry handler** for API rate-limit errors (HTTP 429)
- 🎛 **Customizable generation settings** (temperature, top-p, top-k)
- 🛑 **Easy exit commands:** `stop`, `exit`, `quit`

---

## 🏗 How It Works

The assistant interacts with the Gemini API using the `google.generativeai` Python library.  
User messages are stored in a conversation list, allowing the model to maintain context across multiple turns.

A built-in safety layer blocks inappropriate language, and a retry mechanism ensures stable communication when rate-limit errors occur.

---

## 🚀 Getting Started

Follow these steps to run the project locally:

### **1. Clone the Repository**
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

## 2. Install Dependencies

Make sure you have **Python 3.9+** installed.

```bash
pip install google-generativeai


