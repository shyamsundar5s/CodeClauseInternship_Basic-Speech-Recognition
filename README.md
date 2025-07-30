# CodeClauseInternship_Basic-Speech-Recognition
This repository demonstrates a simple speech recognition system in Python using the `speech_recognition` library. The project enables voice-based command recognition, responding to "hello" and "goodbye" commands.

## Features

- Listens for microphone input and recognizes spoken words.
- Responds to "hello" and "goodbye" with predefined messages.
- Provides feedback if speech is not recognized or an unhandled word is spoken.

## How It Works

1. The system uses the microphone to listen for input.
2. It recognizes speech using Google's Speech Recognition API.
3. On hearing "hello", it responds with "Hello there!".
4. On hearing "goodbye", it responds with "Goodbye!" and exits.
5. For any other input, it prints a default message.
