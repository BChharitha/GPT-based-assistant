# GPT-based-assistant

This project is an AI-based voice assistant that takes user voice commands, generates responses using OpenAI's GPT model, and provides spoken responses. The assistant can also open web applications such as YouTube or Google upon command.

## Features
- **Voice Recognition**: Uses `speech_recognition` to convert spoken commands into text.
- **GPT-4 Language Model Integration**: Utilizes OpenAI's GPT model to process text-based queries and provide intelligent responses.
- **Text-to-Speech**: Uses `pyttsx3` to convert the assistant's responses into speech.
- **Web Browsing**: Opens websites like YouTube and Google upon specific commands.

## Prerequisites
Ensure you have the following packages installed:
```bash
pip install openai SpeechRecognition pyttsx3 pyaudio
