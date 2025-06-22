# 🧠 Sathwik Voice Assistant

A smart desktop voice assistant built in Python that listens to your commands and performs actions like playing YouTube videos, opening applications, telling time, searching Wikipedia, and even telling programming jokes — all with your voice!

---

## 🛠️ Tools Required

- Python 3.8 or above  
- VS Code (or any code editor)  
- A microphone  
- Internet connection (for YouTube & Wikipedia)

---

## 🧪 Setup Instructions

### 📁 Step 1: Create Project Folder

```bash
mkdir voice-desktop-assistant
cd voice-desktop-assistant
🌐 Step 2: Create & Activate Virtual Environment
bash
Copy
Edit
python -m venv venv
Activate it:

Windows:

bash
Copy
Edit
venv\Scripts\activate
Mac/Linux:

bash
Copy
Edit
source venv/bin/activate
You’ll see (venv) in terminal – that means it's activated ✅

📦 Step 3: Install Required Libraries
bash
Copy
Edit
pip install SpeechRecognition pyttsx3 pywhatkit wikipedia pyjokes
📚 Libraries Used
Library	Purpose
speech_recognition	Voice to text
pyttsx3	Text to speech (offline)
pywhatkit	Play YouTube videos
wikipedia	Get summaries
pyjokes	Programming jokes
os, sys	Interact with system

🧠 Features
🎤 Recognizes voice commands

🕐 Tells current time

📺 Plays YouTube videos

🌐 Fetches info from Wikipedia

🃏 Tells programming jokes

💻 Opens Chrome or VS Code

👂 Always listening and responding

📄 Example Commands
play nani songs

what's the time

who is Elon Musk

open chrome

open vs code

tell me a joke

exit or stop

▶️ How to Run the Project
After activating the virtual environment, run:

bash
Copy
Edit
python assistant.py
👨‍💻 Developed By
Sathwik Chinta
📧 sathwikprince2004@gmail.com
🔗 GitHub Project
