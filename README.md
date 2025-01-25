
# Virtual Assistant

A Python-based virtual assistant that can perform a variety of tasks such as checking the time and date, searching Wikipedia, playing music, taking screenshots, telling jokes, and even controlling the system (shutdown or restart).

## Features

- **Time and Date**: Tells the current time and date.
- **Wikipedia Search**: Fetches summaries for your queries from Wikipedia.
- **Play Music**: Plays music from your system's Music directory.
- **Take Screenshots**: Captures your screen and saves it.
- **Jokes**: Tells a random joke.
- **Web Browsing**: Opens popular websites like YouTube and Google.
- **Assistant Name Customization**: Allows you to set a custom name for the assistant.
- **System Control**: Shutdown, restart, or exit the assistant.
- **Voice Interaction**: Responds to commands via voice recognition.

## Requirements

- Python 3.6 or higher
- Libraries:
  - `pyttsx3`
  - `speech_recognition`
  - `wikipedia`
  - `webbrowser`
  - `pyautogui`
  - `pyjokes`

Install these libraries using the following command:
```bash
pip install pyttsx3 speechrecognition wikipedia pyautogui pyjokes
```

## Usage

1. Start the assistant by running the program:
   ```bash
   jarvis.py
   ```

2. Use voice commands to interact with the assistant. Example commands:
   - "What is the time?"
   - "What is the date?"
   - "Search Wikipedia for Python programming."
   - "Play music."
   - "Take a screenshot."
   - "Tell me a joke."
   - "Shutdown the system."
   - "Restart the system."
   - "Change your name."

## Future Enhancements

- Add support for reminders and notifications.
- Include weather updates using an API.
- Enhance music search functionality with external streaming platforms.
- Add more commands for system interaction and file management.
- Improve natural language processing for better command understanding.

## Acknowledgments

- [Python Documentation](https://docs.python.org/)
- [Wikipedia API](https://pypi.org/project/wikipedia/)
- [Pyttsx3 Documentation](https://pyttsx3.readthedocs.io/)
- [PyAutoGUI Documentation](https://pyautogui.readthedocs.io/)
- [PyJokes Documentation](https://github.com/pyjokes/pyjokes)

## Author

Developed by [Sayan Mandal](https://github.com/codersayan0).
