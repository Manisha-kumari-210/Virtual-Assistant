# Voice Assistant

This project is a simple voice assistant built using Python, integrating various libraries such as `pyttsx3`, `speech_recognition`, and others to perform tasks like opening websites, playing music, taking screenshots, searching on YouTube, and more.

## Features

- **Voice Commands**: Responds to various voice commands like opening browsers, searching on YouTube, playing music, and more.
- **Text-to-Speech**: Uses `pyttsx3` to respond with a synthesized voice.
- **Speech Recognition**: Converts speech into text using Google's speech recognition API.
- **System Control**: Allows commands to shut down, restart, or lock the system.
- **Web Search**: Opens web pages like Google and Wikipedia or searches YouTube.
- **Music Control**: Plays music from a specified directory.
- **Screenshot Capture**: Takes screenshots and saves them to the disk.

## Prerequisites

Make sure you have Python 3.x installed along with the following libraries:

- `pyttsx3`
- `speech_recognition`
- `datetime`
- `wikipedia`
- `webbrowser`
- `os`
- `random`
- `cv2`
- `pywhatkit`
- `sys`
- `pyautogui`
- `time`
- `operator`
- `requests`

You can install these dependencies using the following command:

```bash
pip install pyttsx3 speechrecognition pywhatkit pyautogui opencv-python wikipedia requests

## How It Works

1. **Initialization**: 
   - The assistant is initialized using the `pyttsx3` library for text-to-speech functionality and `speech_recognition` for converting speech into text.

2. **Voice Interaction**: 
   - Upon starting the program, the assistant greets the user based on the time of day and asks what it can do for them.

3. **Listening for Commands**: 
   - The assistant continuously listens for voice commands and responds accordingly. It is capable of handling a variety of tasks, including:

   - **Searches on YouTube or Google**: 
     - It performs searches based on the user’s spoken input, either on YouTube or Google.

   - **Opens Websites**: 
     - It can launch websites like Wikipedia, Google, and others as per the user’s request.

   - **Plays Music**: 
     - It plays music from a predefined directory specified by the user.

   - **Controls System**: 
     - The assistant can execute system commands like shutdown, restart, or lock the system.

4. **Handling Commands**: 
   - The assistant processes a wide range of commands such as:
     - Opening applications like a browser or Notepad
     - Writing text in Notepad
     - Taking screenshots and saving them
