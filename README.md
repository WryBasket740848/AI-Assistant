# 🎙️ Voice AI Assistant using Gemini & Streamlit

## Overview

Voice AI Assistant is a Python-based application that combines speech recognition, Google's Gemini AI, text-to-speech, and a Streamlit web interface to create an interactive voice-enabled chatbot.

Users can communicate with the assistant either by typing messages or speaking through their microphone. The assistant processes the request using Gemini AI and responds with both text and voice output.

---

## Features

* 🎤 Voice Input using Speech Recognition
* 💬 Chat Interface with Streamlit
* 🤖 Google Gemini 2.5 Flash Integration
* 🔊 Text-to-Speech Responses
* 📝 Chat History Management
* 🎨 Clean Streamlit User Interface
* ⚡ Fast AI-Powered Responses

---

## Technologies Used

* Python
* Streamlit
* Google Gemini API
* SpeechRecognition
* SoundDevice
* SciPy
* Pyttsx3
* Python Dotenv

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/yourusername/voice-ai-assistant.git
cd voice-ai-assistant
```

### Install Dependencies

```bash
pip install streamlit
pip install google-generativeai
pip install python-dotenv
pip install sounddevice
pip install scipy
pip install SpeechRecognition
pip install pyttsx3
```

Or install everything at once:

```bash
pip install streamlit google-generativeai python-dotenv sounddevice scipy SpeechRecognition pyttsx3
```

---

## Configuration

Create a `.env` file in the project directory:

```env
GEMINI_API_KEY=your_api_key_here
```

Replace `your_api_key_here` with your Google Gemini API key.

---

## Project Structure

```text
Voice-AI-Assistant/
│
├── app.py
├── .env
├── requirements.txt
├── README.md
└── assets/
```

---

## Running the Application

Start the Streamlit server:

```bash
streamlit run app.py
```

The application will open automatically in your browser.

---

## How It Works

### Text Chat

1. Enter a question in the chat box.
2. The message is sent to Gemini AI.
3. Gemini generates a response.
4. The response is displayed in the chat window.

### Voice Chat

1. Click the **🎤 Speak** button.
2. Speak into your microphone.
3. Speech is converted to text.
4. The text is sent to Gemini AI.
5. Gemini generates a response.
6. The response is displayed and spoken aloud.

---

## Example Usage

### User

```text
What is Artificial Intelligence?
```

### Assistant

```text
Artificial Intelligence (AI) is a branch of computer science that enables machines to perform tasks that normally require human intelligence.
```

---

## Future Improvements

* Multi-language Support
* Voice Selection Options
* Conversation Export
* AI Memory System
* Document Question Answering
* RAG Integration
* PDF and DOCX Chat Support
* Streaming Responses

---

## Screenshots

Add screenshots of your application here.

```text
screenshots/homepage.png
screenshots/voice-chat.png
```

---

## Learning Outcomes

This project demonstrates:

* Generative AI Integration
* Voice User Interfaces
* Speech Recognition
* Text-to-Speech Systems
* Streamlit Development
* API Integration
* Real-Time AI Applications

---

## Author

### Amal

Computer Science Student

Skills:

* Python
* Generative AI
* LangChain
* Machine Learning
* Streamlit Development
* AI Assistants

---

## License

This project is licensed under the MIT License.

Feel free to fork, modify, and contribute.
