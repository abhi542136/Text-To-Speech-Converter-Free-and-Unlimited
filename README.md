# Text-To-Speech-Converter-Free-and-Unlimited
A Python-based Text-to-Speech (TTS) converter web application with support for multiple languages, customizable pitch, and gender-based voice selection, built using Flask, pyttsx3, gTTS, and Librosa.

## Live Website

- [Click Here to view](https://text-to-speech-free-unlimited.onrender.com)

## Features

- **Multi-language support:** Convert text to speech in various languages like English, Hindi, Spanish, and French.
- **Customizable voice options:** Choose from different gender-based voices.
- **Pitch Adjustment:** Change the pitch of the generated audio.
- **Web Interface:** User-friendly interface built with HTML, CSS, and JavaScript.
- **Automatic cleanup:** Automatically deletes old files to manage disk space.

## User Interface
- ![image](https://github.com/user-attachments/assets/3c6a5eee-d72f-4de9-ad45-36f2c0e4c948)


## Technologies Used

- **Flask:** A lightweight web framework for Python.
- **gTTS (Google Text-to-Speech):** For generating audio from text in different languages.
- **pyttsx3:** To handle different gender voices.
- **Librosa:** For pitch-shifting of audio files.
- **SoundFile:** For saving modified audio files.
- **HTML/CSS/JavaScript:** For the web-based frontend.

## After Generating audio, you can listen it and download it
- ![image](https://github.com/user-attachments/assets/c562a735-8cfd-4313-acff-48e963861e27)


## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/abhi542136/Text-To-Speech-Converter-Free-and-Unlimited.git
    cd Text-To-Speech-Converter-Free-and-Unlimited
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the Flask server:

    ```bash
    python app.py
    ```

4. Open your browser and navigate to `http://127.0.0.1:5000/` to access the application.

## Usage

1. **Enter Text:** Type or paste the text you want to convert into speech.
2. **Select Language:** Choose a language from the dropdown menu.
3. **Select Voice and Pitch:** Pick a gender-based voice and adjust the pitch if desired.
4. **Generate Audio:** Click the "Generate" button to create the audio.
5. **Download Audio:** Click "Download" to save the audio file to your device.

## File Cleanup

- A background process automatically deletes files older than 15 minutes to manage storage.

## Contributions

Contributions are welcome! Please open an issue to discuss your ideas or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Author

- [Abhishek Kumar](https://linkedin.com/in/abhishekiitpatna/)

## Acknowledgements

- [Google Text-to-Speech (gTTS)](https://pypi.org/project/gTTS/)
- [pyttsx3](https://pypi.org/project/pyttsx3/)
- [Librosa](https://pypi.org/project/librosa/)
- [Flask](https://palletsprojects.com/p/flask/)
