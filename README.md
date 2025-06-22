# 🧠 Sathwik Voice Assistant

A smart Python desktop voice assistant that listens to your voice and performs cool actions like playing YouTube songs, opening apps, telling time, searching Wikipedia, and telling jokes.

---

## 🛠️ Tools Required

- Python 3.8 or above  
- VS Code (or any editor)  
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

Windows

bash
Copy
Edit
venv\Scripts\activate
Mac/Linux

bash
Copy
Edit
source venv/bin/activate
📦 Step 3: Install Required Libraries
bash
Copy
Edit
pip install SpeechRecognition pyttsx3 pywhatkit wikipedia pyjokes
📚 Libraries Used
Library	Purpose
speech_recognition	Convert voice to text
pyttsx3	Convert text to speech (offline)
pywhatkit	Play YouTube videos
wikipedia	Get topic/person summaries
pyjokes	Tell programming jokes
os, sys	Open apps, handle exit

🧠 Features
🎤 Recognizes voice commands

🕐 Tells current time

📺 Plays YouTube videos

🌐 Wikipedia info fetcher

🃏 Tells programming jokes

💻 Opens Chrome or VS Code

🔁 Always listening and responding

📄 Example Commands
play nani songs

what's the time

who is Elon Musk

open chrome

open vs code

tell me a joke

exit or stop

✅ No YouTube link needed – it auto-plays using your voice.

▶️ How to Run the Project
After activating the virtual environment, run:

bash
Copy
Edit
python assistant.py
Then just speak your commands 🎙️

👨‍💻 Developed By
Sathwik Chinta
📧 sathwikprince2004@gmail.com
🔗 GitHub Project
