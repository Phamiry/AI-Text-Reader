
# AI Text Reader — Project Planning Document

## 1. Problem Statement

Reading large amounts of digital text can be inconvenient for people who prefer listening or need to review information while performing other activities. AI Text Reader addresses this problem by converting written text into spoken audio using AI-powered text-to-speech technology.

## 2. Project Objectives

- Develop a Python application that converts text into speech.
- Allow users to enter text or load a text file.
- Generate audio using the ElevenLabs API.
- Play and save the generated speech.
- Apply AI-assisted development practices to improve code quality, testing, and documentation.

## 3. Functional Requirements

The application is designed to:

1. Accept text entered directly by the user.
2. Read text from a local `.txt` file.
3. Generate speech using the ElevenLabs API.
4. Play generated audio.
5. Save generated speech as an MP3 file.
6. Handle invalid menu selections and missing files.
7. Retrieve the API key from a private environment variable.

## 4. System Features

- Command-line menu for text input.
- Support for text-file input.
- AI-powered speech generation.
- Audio playback.
- MP3 file output.
- Basic input validation and error handling.

## 5. Software Design

AI Text Reader uses a command-line architecture with separate functions for reading files, generating speech, and saving audio.

The intended workflow is:

User Input → Text Processing → ElevenLabs API → Audio Generation → Playback and MP3 Saving

The program is written in Python and uses the ElevenLabs library to communicate with the speech-generation service.

## 6. Technology Stack

- **Programming language:** Python
- **AI service:** ElevenLabs API
- **Audio tools:** ElevenLabs playback library and FFmpeg
- **Development environment:** Visual Studio Code
- **Version control:** Git and GitHub
- **AI development assistance:** ChatGPT

## 7. Development Timeline

This project originated as a Fall 2024 Artificial Intelligence course project. The following phases describe its development and current adaptation for the AI-Assisted Software Development assignment.

| Phase | Activities |
|---|---|
| 1. Initial planning | Define the problem, objectives, and features |
| 2. Original development | Build the Python text-to-speech application |
| 3. Troubleshooting | Address Python environment, FFmpeg, and API configuration issues |
| 4. Repository preparation | Organize the source files and README in GitHub |
| 5. Documentation | Prepare requirements, planning documentation, and AI usage evidence |
| 6. Testing and final review | Verify application behavior, document results, and prepare the submission |

## 8. Testing 

Testing should confirm that the application accepts direct text input, reads valid text files, handles missing files, generates speech, plays audio, and saves an MP3 file.

  
