# JARVIS - Voice Assistant

JARVIS is a simple voice assistant built using JavaScript. It can respond to various voice commands such as greetings, opening websites, searching the web, and providing basic information like time and date.

## Features

- **Voice Commands**: JARVIS listens to your voice commands and responds accordingly.
- **Speech Synthesis**: JARVIS speaks back to you, providing a seamless interaction.
- **Opens Popular Websites**: You can open Google, YouTube, Facebook, Instagram, and more with voice commands.
- **Search the Web**: Automatically opens a browser search based on your query.
- **Checks Time & Date**: JARVIS can tell you the current time and date.
- **Wikipedia Search**: Directly searches Wikipedia based on your voice query.
- **Cross-Browser Support**: Works in browsers that support `SpeechRecognition` and `SpeechSynthesis`.

## Technologies Used

- **JavaScript**: Core language for functionality.
- **Web Speech API**: Used for speech recognition and speech synthesis.
  - `SpeechRecognition` for recognizing voice commands.
  - `SpeechSynthesis` for converting text into speech.

## Voice Commands

Here are some example commands JARVIS can respond to:

- **Greetings**: "Hey", "Hello"
- **Assistant Info**: "Who are you?", "What is your name?"
- **Open Websites**: "Open Google", "Open YouTube", "Open Facebook", "Open Instagram"
- **Time and Date**: "What time is it?", "What's the date today?"
- **Web Search**: "What is [topic]?", "Who is [person]?"
- **Wikipedia Search**: "Search [topic] on Wikipedia"
- **Other Features**: "Open Calculator", "Open ChatGPT"

## Project Structure

- `index.html`: The main file that includes the interface and JavaScript.
- `app.js`: Contains all the logic for voice recognition, command processing, and speaking.
- `styles.css`: Basic styling for the interface.
