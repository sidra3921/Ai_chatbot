# Ai_chatbot
# Simple Chatbot 🤖

A simple AI chatbot built with **Streamlit** and **Google Gemini API**. It allows users to chat with an AI assistant in real time through a clean web interface.

## 🚀 Features

* Real-time AI chat using Gemini 1.5 Flash
* Chat history stored in session
* Simple and clean UI with Streamlit chat interface
* Environment variable support for API key

## 🛠️ Tech Stack

* Python
* Streamlit
* Google Generative AI (Gemini)
* Python-dotenv

## ⚙️ Setup Instructions

### 1. Install dependencies

```bash
pip install streamlit google-generativeai python-dotenv
```

### 2. Add API Key

Create a `.env` file in the project root:

```
GEMINI_API_KEY=your_api_key_here
```

### 3. Run the app

```bash
streamlit run app.py
```

## 📌 How it works

* User types a message
* Message is sent to Gemini API
* AI response is generated and displayed in chat
* Conversation is stored in session state

## 👩‍💻 Author

Sidra
