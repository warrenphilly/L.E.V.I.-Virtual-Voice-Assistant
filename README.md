# AI Speech Assistant "L.E.V.I."

## Overview
L.E.V.I. (Logic Empowered Visionary Interface) is a Python application functioning as an AI-powered speech assistant. It integrates speech recognition and text-to-speech capabilities, communicating with OpenAI's GPT-4 model. The assistant has a sassy personality, humorously referring to the user as "boss" while playfully considering them less intelligent.

## Features
- **Speech Recognition**: Captures spoken words via a microphone and converts them to text.
- **Text-to-Speech**: Converts textual AI responses into audible speech.
- **ChatGPT Interaction**: Sends user inputs to OpenAI's GPT-4 model and receives AI-generated responses.
- **Asynchronous Processing**: Efficiently handles network requests and AI interactions.

## Requirements
- Python 3.x
- OpenAI API Key
- Speech Recognition Library (`speech_recognition`)
- Python Text to Speech v3 (`pyttsx3`)
- Playsound Library (`playsound`)
- aiohttp
- Python-dotenv (`dotenv`)
- OpenAI Python Library (`openai`)

## Setup
1. **Install Dependencies**:
   ```bash
   pip install speech_recognition pyttsx3 playsound aiohttp python-dotenv openai
## Enviroment Variables
1. **create a '.env' file in your root directory.**
2. **Add you OpenAi API key.**:
   ```bash
   OPENAI_KEY=your_api_key_here
## Run the Application
- **Run the Command**:
   ```bash
   python path_to_script.py
   
## Usage
- **Start the Application**: Run the script and the assistant starts listening.
- **Interact with L.E.V.I.**:Speak to the assistant for AI-generated responses.
- **End Session**: Stop the script to end the interaction.

## Note
- Ensure a stable internet connection.
- Adjust microphone settings for better voice recognition.

## Disclaimer
- This application utilizes OpenAI's GPT-4, which may incur costs.
  
  

  
