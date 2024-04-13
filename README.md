FORTANA - Voice-Controlled Assistant

FORTANA is a voice-controlled assistant application developed using Python. It enables users to interact with their computer through voice commands, performing various tasks from opening applications to fetching information from the web.
Features

    Voice Interaction:
        FORTANA responds to voice commands using pyttsx3 for text-to-speech and speech_recognition for speech recognition.
        The assistant can understand and execute various voice commands such as opening applications, fetching news, playing music, and more.

    Utility Functions:
        Opens common applications like Notepad, Adobe Reader, and Command Prompt upon voice command.
        Provides news updates using the News API.
        Reads PDF documents aloud using PyPDF2.
        Takes screenshots and performs tasks based on recognized commands.

    Additional Functionalities:
        Can perform basic calculations based on voice input.
        Retrieves information from Wikipedia.
        Controls system actions like shutdown, restart, and sleep using voice commands.
        Interacts with web services such as YouTube, Facebook, Google, and Stack Overflow.

Requirements

Ensure you have the necessary dependencies installed to run FORTANA:

    pyttsx3 - Text-to-speech library for voice output.
    speech_recognition - Library for recognizing speech input.
    wikipedia - For fetching information from Wikipedia.
    pyjokes - Retrieves random jokes.
    pyautogui - Allows interaction with the GUI, useful for taking screenshots.
    PyPDF2 - Enables reading and extracting text from PDF documents.
    requests - Library for making HTTP requests.
    opencv-python - For camera functionality.

Additional Notes

    Ensure your system has a microphone for voice input.
    Customize or extend FORTANA by adding more commands and functionalities based on your requirements.
