# python-speech-projects

This repository contains two Jupyter Notebook projects demonstrating basic speech recognition in Python.  
You can convert speech to text and even open websites using your voice.

---

##  Project Files

###  **Speech_Recognition.ipynb**
A simple speech-to-text notebook.

**Features:**
- Listens through your microphone
- Adapts to background noise
- Converts your speech to text using Google Speech Recognition
- Handles recognition errors

---

###  **Speech_Recognition_to_website.ipynb**
A voice-controlled browser opener.

**Features:**
- Takes voice input
- Detects the website name you say
- Opens the website using Microsoft Edge (can be replaced with any browser)

Example:  
Say **"youtube.com"** → Microsoft Edge opens YouTube.

---

##  What You Need to Install

Before running the notebooks, install these Python libraries:

```bash
pip install SpeechRecognition
pip install pyttsx3
pip install pyaudio
