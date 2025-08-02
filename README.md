# elderly-assistant-bot
# Jarvis - Voice-Controlled AI Assistant

A Python-based voice assistant that combines speech recognition, text-to-speech, and AI capabilities to create an interactive personal assistant.

## Features

- **Voice Recognition**: Listens for voice commands starting with "Jarvis"
- **Natural Speech Output**: Uses gTTS (Google Text-to-Speech) with UK English voice
- **AI Integration**: Powered by Google's Gemini AI for natural conversations
- **Multiple Command Functions**:
  - Time checking
  - Application launching (Chrome, Notepad, YouTube)
  - Weather updates (using WeatherAPI)
  - Wikipedia searches
  - Language translation
  - General AI-powered conversations

## Prerequisites

- Python 3.x
- Working microphone
- Internet connection
- API Keys:
  - Gemini API key
  - WeatherAPI key

## Installation

1. Clone the repository
2. Install required packages:
```bash
pip install -r requirements.txt
```
3. Create a `.env` file in the root directory with your API keys:
```env
GEMINI_API_KEY=your_gemini_api_key
WEATHER_API_KEY=your_weather_api_key
```

## Usage

1. Run the program:
```bash
python jarvis/nepy.py
```

2. Wait for the "Hello, I am Jarvis. How can I help you?" greeting

3. Start commands with "Jarvis" followed by your request:
   - "Jarvis what time is it?"
   - "Jarvis open chrome"
   - "Jarvis weather in London"
   - "Jarvis who is Albert Einstein?"
   - "Jarvis translate hello to Spanish"

## Voice Commands

- **Time**: "Jarvis what time is it?"
- **Open Applications**: 
  - "Jarvis open chrome"
  - "Jarvis open notepad"
  - "Jarvis open youtube"
- **Weather**: "Jarvis weather in [city]"
- **Information**: 
  - "Jarvis who is [person]?"
  - "Jarvis what is [topic]?"
- **Translation**: "Jarvis translate [text] to [language]"
- **Exit**: "Jarvis exit" or "Jarvis stop" or "Jarvis quit"

## Error Handling

- Voice recognition errors are gracefully handled with appropriate messages
- Network connectivity issues are managed with user-friendly notifications
- API errors provide clear feedback for troubleshooting

## Dependencies

- SpeechRecognition
- pyttsx3
- requests
- wikipedia
- pyautogui
- googletrans (version 4.0.0rc1)
- pygame
- python-dotenv
- gTTS

## Notes

- The program requires active internet connection for voice recognition and AI features
- Ensure microphone permissions are enabled for the application
- API keys must be valid and active for full functionality

## License

This project is open-source and available under# elderly-assistant-bot
# elderly-assistant-bot
# elderly-assistant-bot
