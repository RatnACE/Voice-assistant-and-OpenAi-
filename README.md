# Voice Assistant Program README

This program is a voice assistant built using Python that utilizes the OpenAI GPT-3 language model to provide responses to user commands and questions. The voice assistant is capable of converting speech to text using the SpeechRecognition library and synthesizing speech using the pyttsx3 library.

## Prerequisites

To run this program, you need to have the following dependencies installed:

- Python 3.x
- openai module (`pip install openai`)
- pyttsx3 module (`pip install pyttsx3`)
- speech_recognition module (`pip install SpeechRecognition`)

## Getting Started

1. Clone or download the program files to your local machine.

2. Obtain an API key from OpenAI by signing up for their services.

3. Replace `''` on line 30 with your OpenAI API key.

4. Run the program using a Python interpreter.

   ```
   python voice_assistant.py
   ```

## Usage

1. When the program starts, it will greet you and wait for your command.

2. Simply speak your command into the microphone connected to your computer.

   - The program will recognize your speech and display your command.

3. The program will send your command to the OpenAI GPT-3 language model for processing.

   - The model will generate a response based on your command.

4. The generated response will be displayed and spoken aloud by the voice assistant.

5. If you want to exit the program, say "exit" during your command, and the program will terminate.

## Notes

- Ensure that your computer has a working microphone and speaker system for voice input and output.

- The program uses the `en-in` language setting for speech recognition, which can be modified in the `takeCommand` function if needed.

- The OpenAI API key is required for the program to function properly. Make sure to keep your API key secure and avoid sharing it.

- The program uses the `text-davinci-002` model from OpenAI for generating responses. You can explore other models provided by OpenAI based on your requirements.

- Adjustments can be made to the temperature, max tokens, top-p, frequency penalty, and presence penalty parameters in the `run` function to fine-tune the response generation.


## Acknowledgments

- This program was developed using the OpenAI GPT-3 language model, which is a powerful tool for generating human-like text.

- The pyttsx3 and SpeechRecognition libraries were used to handle speech synthesis and speech recognition functionalities in Python.

- Special thanks to the developers and contributors of the mentioned libraries and tools for making this program possible.
