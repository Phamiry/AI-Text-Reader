
# AI Text Reader — Software Requirements

## Project Scope

AI Text Reader is a Python command-line application that converts typed text or text from a local file into AI-generated speech using the ElevenLabs API.

## Functional Requirements

1. The application shall allow users to enter text directly.
2. The application shall allow users to read text from a local text file.
3. The application shall send the selected text to the ElevenLabs API for speech generation.
4. The application shall play the generated audio.
5. The application shall save the generated speech to an MP3 file.
6. The application shall handle invalid input selections and missing text files.
7. The application shall load its ElevenLabs API key from an environment variable.

## Non-Functional Requirements

1. The application shall use Python and the ElevenLabs Python library.
2. The application shall provide readable command-line instructions.
3. The application shall avoid storing API keys in source code.
4. The application should give understandable error messages when possible.
5. The application shall require an internet connection for ElevenLabs speech generation.

## Assumptions

- Python and the necessary dependencies are installed.
- The user has access to an ElevenLabs API key.
- The user's computer has a working audio output device.
- The user has permission to access the text files being read.

## Out of Scope

- Real-time speech recognition.
- Training custom voice models.
- A graphical user interface.
- Voice cloning without the speaker's consent.
  
