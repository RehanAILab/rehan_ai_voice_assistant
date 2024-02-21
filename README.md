# Rehan AI Voice Assistant

This is a Flask-based Voice Assistant application using OpenAI's GPT-3.5 Turbo for natural language processing and pygame for audio playback.

## Prerequisites

- Python 3.6 or higher
- [pygame](https://www.pygame.org/) library
- OpenAI API Key

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/MuhammadNasarUddin/voice-assistant.git
    ```

2. Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

3. Set up your OpenAI API Key. Create a `.env` file in the project root and add:

    ```plaintext
    openai_api_key=your_openai_api_key
    ```

## Usage

1. Run the Flask application:

    ```bash
    python app.py
    ```

2. Open your browser and go to [http://localhost:5000](http://localhost:5000).

3. Choose your preferred language (English or Urdu) and click on the microphone button to start voice recognition.

4. Speak clearly and ask your question. The assistant will generate a response using GPT-3.5 Turbo.

## Folder Structure

- `/static`: Contains static files such as images and generated audio files.
- `/templates`: HTML templates for Flask.

