# 🧠 Sathwik Voice Assistant

A smart desktop voice assistant built in Python that responds to your voice commands to perform tasks like playing YouTube videos, telling the time, fetching Wikipedia information, opening applications, and telling programming jokes.

---

## 🛠️ Requirements

- Python 3.8 or above  
- Visual Studio Code (or any code editor)  
- Microphone  
- Internet connection (for YouTube/Wikipedia features)

---

## ⚙️ Setup Instructions

### 1️⃣ Create and Navigate to Project Folder

```bash
mkdir voice-desktop-assistant
cd voice-desktop-assistant
2️⃣ Create & Activate Virtual Environment
bash
Copy
Edit
python -m venv venv
Activate it:

On Windows:

bash
Copy
Edit
venv\Scripts\activate
On Mac/Linux:

bash
Copy
Edit
source venv/bin/activate
3️⃣ Install Required Libraries
bash
Copy
Edit
pip install SpeechRecognition pyttsx3 pywhatkit wikipedia pyjokes
📚 Libraries Used
Library	Purpose
speech_recognition	Convert voice to text
pyttsx3	Convert text to speech (offline)
pywhatkit	Play YouTube videos
wikipedia	Fetch summaries from Wikipedia
pyjokes	Generate programming jokes
os, sys	Open apps and handle system exit

💡 Features
🎙️ Voice command recognition

⏰ Tells current time

📺 Plays YouTube videos

🌐 Provides Wikipedia summaries

🃏 Tells programming jokes

💻 Opens applications (Chrome, VS Code)

🔁 Runs continuously, always listening

🗣️ Example Voice Commands
play nani songs

what's the time

who is Elon Musk

open chrome

open vs code

tell me a joke

exit or stop

✅ No need to provide YouTube links – videos are fetched automatically based on voice input.

▶️ Running the Project
Activate your virtual environment and run:

bash
Copy
Edit
python assistant.py
Speak your command and watch the assistant respond in real time!

👨‍💻 Developed By
Sathwik Chinta
📧 sathwikprince2004@gmail.com
🔗 GitHub Repository

🗂️ Optional: Project Metadata (YAML)
For automation or DevOps purposes, you may include a basic metadata file like this:

yaml
Copy
Edit
project: Sathwik Voice Assistant
author: Sathwik Chinta
email: sathwikprince2004@gmail.com
language: Python
future_use:
  - Voice assistant project
  - Speech recognition features
  - YouTube + Wikipedia integration
  - Application launcher
📌 License
This project is licensed under the MIT License.
Feel free to use, modify, and share it with credit.
