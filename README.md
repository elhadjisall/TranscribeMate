# Freescribe

Freescribe is a React Based web application that allows users to transcribe audio by directly recording from a microphone or by uploading custom .mp3 files. The transcribed text can then be translated into different languages using machine learning models.

![Homepage Screenshot](./src/assets/Screenshot%202024-07-26%20184848.png)  

## Features

- **Audio Transcription:** Record audio directly from your microphone or upload .mp3 files to convert speech to text.
- **Language Translation:** Translate transcribed text into multiple languages using state-of-the-art machine learning models.

## Live Demo

Check out the live demo of the application [here](https://freescribee.netlify.app/).

## Technologies Used

- React.js
- Tailwind CSS
- **Transcription ML Model:** [openai/whisper-tiny.en](https://github.com/openai/whisper)
- **Translation ML Model:** [Xenova/nllb-200-distilled-600M](https://github.com/Xenova/nllb-200-distilled-600M)

## Installation

To get a local copy up and running, follow these simple steps:

1. Clone the repository
   ```sh
   git clone https://github.com/your_username/Freescribe.git

2. Navigate to the project director
   ```sh
   cd Freescribe

3. Install dependencies
   ```sh
   npm install

4. Run the application
   ```sh
   npm start

## Usage

1. Transcribing Audio:

- Click on the microphone icon to start recording audio directly from your browser.
- Alternatively, upload a .mp3 file from your device.

2. Translating Text:

- After transcription, select the desired language to translate the text.