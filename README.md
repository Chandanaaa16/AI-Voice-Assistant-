# 🗣️ AI Voice Assistant

An intelligent voice-controlled assistant built using Python and NLP libraries, capable of understanding user commands and performing real-time tasks through speech.

## 📌 Overview
This project simulates a personalized voice assistant (like Alexa or Siri) that listens to your voice, interprets your commands, and responds appropriately. The assistant can perform tasks such as telling the time, opening websites, fetching quick information from Wikipedia, and more.

It achieved over **95% accuracy** in command interpretation during local testing.

## 🎯 Features
- Real-time voice recognition and response
- Personalized greetings and command fallback handling
- Can open websites, tell time/date, fetch Wikipedia summaries
- Easily extendable architecture for more features

## 🛠️ Tech Stack
- **Language:** Python
- **Libraries:**
  - `speech_recognition`
  - `pyttsx3`
  - `datetime`, `webbrowser`, `os`
  - `wikipedia`, `requests`



## 🖥️ How to Run (Using PyCharm)

1. **Clone or download** the repository into your local system.
2. **Open the folder in PyCharm.**
3. Ensure Python 3 is configured in your interpreter.
4. Install required packages:
    ```bash
    pip install -r requirements.txt
    ```
5. Run `voice_assistant.py` directly from PyCharm.

### ⚠️ Prerequisites
- Python 3.x installed
- Working microphone
- Stable internet connection (for API-based features)


