Oasis_Infobyte_Voice_Assistant.py
To create a basic voice assistant, you'll want to focus on a few key features. First, implement a greeting response to "Hello" with predefined replies. Next, integrate functionality to tell the current time and date. Finally, add a web search capability to respond to user queries.

You can use Python libraries such as speech_recognition for voice input, pyttsx3 for text-to-speech, and selenium for web searching. Below is a structured approach to building this voice assistant.

1. Required Libraries

speech_recognition: For recognizing voice commands.
pyttsx3: For converting text to speech.
datetime: To fetch the current time and date.
selenium: For web searching.

4. Explanation of the Code

Speech Recognition: The listen function captures audio input and converts it to text using Google's speech recognition.

Text-to-Speech: The speak function uses pyttsx3 to convert text responses into speech.

Time and Date: The tell_time and tell_date functions fetch and announce the current time and date.

Web Search: The search_web function opens a web browser to search for the user's query.

5. Running the Assistant

Run the script in an environment where you have microphone access.
Speak commands like "Hello", "What time is it?", "What is the date?", or "Search for Python programming".
This basic voice assistant can be expanded with more features such as weather updates, jokes, or integration with other APIs for enhanced functionality.
