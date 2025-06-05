# Jarvis Voice Assistant

A simple Python-based personal assistant that responds to text commands and performs tasks like searching Wikipedia, opening websites, playing music, telling the time, and sending emails.

## Features

- Greets the user based on the time of day.
- Searches Wikipedia and reads summaries aloud.
- Opens popular websites like YouTube, Google, and StackOverflow.
- Plays music from a specified directory.
- Tells the current time.
- Sends emails via SMTP.
- Responds to basic identity questions.
- Opens installed applications like Dev C++ or VS Code.

## Requirements

- Python 3.x
- Packages: `pyttsx3`, `wikipedia`, `SpeechRecognition`, `datetime`, `webbrowser`, `os`, `smtplib`

Install required packages using:

```bash
pip install pyttsx3 wikipedia SpeechRecognition
