# 🗣️ Jimmy – Voice Assistant for Windows

**Jimmy** is a multi-functional, hands-free voice assistant built with **Python** that listens, understands, and performs real-world tasks using simple voice commands.  

From playing YouTube videos to sending WhatsApp messages, Jimmy brings smart automation to your desktop — no clicks needed.  

---

## 🚀 Features

- 🎵 **Play Music or Videos:** “Jimmy, play Shape of You on YouTube.”  
- 🔍 **Search the Web:** “Jimmy, search latest AI news.”  
- 🧠 **Get Instant Info:** “Jimmy, define neural networks.”  
- 🕒 **Check the Time:** “Jimmy, what’s the time?”  
- 😂 **Tell Jokes:** “Jimmy, tell me a joke.”  
- 💻 **System Control:** “Jimmy, shutdown the computer.”  
- 💬 **Send WhatsApp Messages:** “Jimmy, send hello to Kalyan.”  
- 👋 **Interactive Responses:** Personalized greetings and witty replies (“I’m in a relationship with Wi-Fi”).  

---

## 🧩 Tech Stack

- **Python 3.8+**  
- **SpeechRecognition** – Voice command recognition  
- **PyAudio** – Microphone input  
- **pyttsx3** – Text-to-speech  
- **PyWhatKit** – YouTube, WhatsApp & Web automation  
- **Wikipedia API** – Information lookup  
- **PyJokes** – Humor integration

---

##🧠 How It Works

1. Jimmy listens for voice input via your microphone.
2. Commands are recognized using Google Speech Recognition.
3. Depending on keywords (play, time, search, send), the assistant performs the appropriate task.
4. Responses are spoken back using pyttsx3 for a natural experience.

---

### Add or modify contacts in the contacts dictionary:

contacts = {'robert': '+9196529104**', 'kalyan': '+919958***'}

### Adjust voice preferences in the initialization section:

voices = engine.getProperty('voices')
engine.setProperty('voice', voices[1].id)  # Change voice

