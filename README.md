Jimmy – Voice Assistant for Windows

Jimmy is a multi-functional, hands-free voice assistant built with Python that listens, understands, and performs real-world tasks using simple voice commands.

From playing YouTube videos to sending WhatsApp messages, Jimmy brings smart automation to your desktop — no clicks needed.

🚀 Features

🎵 Play Music or Videos: “Jimmy, play Shape of You on YouTube.”

🔎 Search the Web: “Jimmy, search latest AI news.”

🧠 Get Instant Info: “Jimmy, define neural networks.”

🕒 Check the Time: “Jimmy, what’s the time?”

💬 Tell Jokes: “Jimmy, tell me a joke.”

💻 System Control: “Jimmy, shutdown the computer.”

💬 Send WhatsApp Messages: “Jimmy, send hello to Kalyan.”

👋 Interactive Responses: Personalized greetings and witty replies (“I’m in a relationship with Wi-Fi”).

🧩 Tech Stack

Python 3.8+

SpeechRecognition
 – Voice command recognition

PyAudio
 – Microphone input

pyttsx3
 – Text-to-speech engine

PyWhatKit
 – YouTube, WhatsApp & web automation

Wikipedia
 – Information retrieval

PyJokes
 – Humor integration




🧠 How It Works

Jimmy continuously listens for voice input through your microphone.

Commands are recognized using Google Speech Recognition.

Based on keywords (e.g., play, time, search, send), Jimmy executes the relevant task.

Responses are spoken back using a natural voice via pyttsx3.

📞 Customization

Add new contacts in the contacts dictionary:

contacts = {'robert': '+919652910494', 'kalyan': '+919959017634'}


Modify or add new command logic in the run_Jimmy() function.

Change Jimmy’s voice in the initialization block:

voices = engine.getProperty('voices')
engine.setProperty('voice', voices[1].id)  # Switch voice
