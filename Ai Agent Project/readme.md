# ✨ AI Agent

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
git clone https://github.com/ranaparvez844/Ai-Course.git

### **2. Install Dependencie** 

Make sure you have **Python 3.9+** installed.


pip install google-generativeai

### **3. Add Your Gemini API Key**

(api_key="Don't share your api key, use own API key ")

### **4. Run the Assistant**

python main.py


##  📸 Demo Screenshot
<img width="653" height="227" alt="Image" src="https://github.com/user-attachments/assets/3d73763b-d624-41bf-92fa-f04623d4a130" />
