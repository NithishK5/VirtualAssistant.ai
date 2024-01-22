# Voice-Controlled Assistant (Mia)

## Description
This Python script establishes a basic voice-controlled assistant named Mia. Utilizing speech recognition, it processes voice commands to perform tasks like playing music on YouTube or informing about the current time.

## Features
- **Voice Recognition:** Captures voice commands using a microphone.
- **Music Playback:** Plays requested songs on YouTube.
- **Time Inquiry:** Responds with the current time.

## Requirements
Install the following Python libraries:
- `speech_recognition`
- `pyttsx3`
- `pywhatkit`
- `datetime`

Use pip for installation:
pip install SpeechRecognition pyttsx3 pywhatkit

## Setup and Execution
1. Initializes speech recognition and text-to-speech engine.
2. Sets voice properties for the text-to-speech engine.
3. `talk` function: Enables the assistant to vocalize text.
4. `take_command` function: Converts spoken words into text.
5. `run_mia` function: Interprets and acts upon the commands.

## Usage
- Execute the script.
- Speak a command after "Listening..." appears.
- Example Commands:
   - "Mia, play Shape of You."
   - "Mia, what's the time?"

## Important Notes
- A stable internet connection is required.
- Speech recognition accuracy may vary.
- The keyword 'mia' should precede all commands.


