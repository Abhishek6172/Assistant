# 🧠 AI Voice Assistant — Siri-Inspired Interface

A powerful desktop AI assistant featuring a Siri-like animated wave UI, voice interaction, and chat memory — built with **Python**, **Eel**, **HTML/CSS/JS**, and **Marte LLM** integration.

---

## 🚀 Features

- 🎙️ **Voice Commands**: Start with a click or keyboard shortcut (`X`)
- 🌊 **Siri-Style Wave Animation** using `siriwave.js`
- 🗣️ **Text-to-Speech Responses** (via `pyttsx3`)
- 🤖 **LLM Integration** using Marte API (OpenAI compatible)
- 💬 **Chat-style Messaging UI** (You + Assistant)
- 🧠 Remembers conversation until you say “Thank you”
- 🎥 **Background video** + animated transitions
- ❌ Instantly cancel with keypress (`X`) during speech
- 🕶 Fully local UI + silent console output

---

## 📂 Project Structure

PROJECT5_AI/
├── engine/
│ ├── command.py # Voice control and main loop
│ ├── gpt.py # Marte API integration
│ ├── features.py # OS commands / file open
│ └── config.py # API keys and configuration
├── www/
│ ├── index.html # Assistant UI
│ ├── main.js # Frontend logic (eel + UI)
│ ├── style.css # Assistant styles
│ ├── assets/ # Videos, icons, animations
│ └── eel.js # Eel bridge
├── main.py # Entry point
├── .gitignore
└── README.md

### 1. Clone the repo
```bash
git clone https://github.com/Abhishek6172/Assistant.git

### 2.requirements
eel==0.16.0
pyttsx3==2.90
SpeechRecognition==3.10.1
requests==2.31.0
urllib3==2.2.1
pyaudio==0.2.13
certifi==2024.2.2




🙌 Credits
Marte LLM
SiriWave.js
Eel


---

Let me know if you want:

- `LICENSE` file (MIT or Apache)  
- `.gitignore` for Python & VS Code  
- GitHub repo name suggestions (like `siri-assistant` or `voice-genius`)  
 Thank You


