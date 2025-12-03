# Translator - Real-Time Speech & Text Translation

A Flask web application for translating text and speech in real-time using Google Translate.

## Features

- **Text Translation**: Easily translate text between multiple languages
- **Live Speech Translation**: Translate spoken words in real-time using your microphone
- **Audio File Support**: Upload and translate audio files
- **Simple Web Interface**: Clean and user-friendly web UI

## Installation

Install dependencies:
```bash
py -3.10 -m pip install -r requirements.txt
```

## How to Use

1. Start the application:
```bash
py -3.10 app.py
```

2. Open your browser and go to `http://127.0.0.1:5000`

3. Choose your translation method:
   - **Text**: Type text and select languages to translate
   - **Speech**: Click microphone to record and translate spoken words

## Built With

- Flask
- Google Translate API
- SpeechRecognition
- PyAudio
- pydub
