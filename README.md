# Voice-to-Image Generator

This Streamlit application converts spoken words into images using OpenAI's Whisper for speech-to-text and DALL-E 2 for text-to-image generation.

## Features

- Audio recording through the user's microphone
- Speech-to-text conversion using OpenAI's Whisper model
- Image generation based on transcribed text using DALL-E 2
- Simple, user-friendly interface powered by Streamlit

## Installation

1. Clone this repository:https://github.com/parvej8461/voice-to-image-generator.git
cd voice-to-image-generator
2. Install the required dependencies:
3. Set up your OpenAI API key:
- Create a `.env` file in the project root
- Add your OpenAI API key to the `.env` file:
  ```
  OPENAI_API_KEY=your_api_key_here
  ```

## Usage

1. Run the Streamlit app:
2. Open your web browser and go to the URL provided by Streamlit (usually `http://localhost:8501`)

3. Click the "Click here to speak" button and speak for 5 seconds

4. Wait for the app to process your speech and generate an image

5. View the transcribed text and generated image on the page

## Dependencies

- Python 3.7+
- Streamlit
- sounddevice
- wavio
- OpenAI API
- requests

## Configuration

The app uses OpenAI's Whisper model for speech recognition and DALL-E 2 for image generation. Make sure you have the necessary API access and credits from OpenAI to use these models.

## Known Issues

- The audio file naming is inconsistent between recording and transcription. This will be fixed in a future update.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.


## Acknowledgments

- OpenAI for providing the Whisper and DALL-E 2 models
- Streamlit for the web application framework
