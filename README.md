# Language Translation App

This is a simple and interactive **Language Translation App** built using **Streamlit**, **Google Translate API**, and **gTTS** (Google Text-to-Speech). The app allows users to input text in any language, translate it into a target language, and listen to the translated text through generated speech.

## Features

- **Text Translation:** Input text can be translated into any target language.
- **Text-to-Speech:** Translated text is converted to speech, and users can listen to it.
- **Multiple Language Support:** Select from a variety of languages for translation and audio playback.

## Requirements

To run this app, you will need to install the following Python libraries:

- `streamlit`
- `googletrans`
- `gtts`

You can install them using `pip`:

```bash
pip install streamlit googletrans gtts
How to Run
Clone this repository or download the necessary files.

Ensure you have the required libraries installed.

Run the following command to start the Streamlit app:

bash
Copy code
streamlit run app.py
Open the app in your web browser (usually at http://localhost:8501).

Usage
Enter text to translate: In the input text area, type the text that you want to translate.
Select a target language: Choose the target language from the dropdown list.
Translate the text: Click the "Translate" button to see the translated text.
Listen to the translation: After translation, click on the speaker icon 🔊 to hear the translated text in speech.
Supported Languages
The app supports a variety of languages for translation and speech generation, thanks to the googletrans API. The supported languages are available in the languages.py file.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments
Streamlit: A powerful framework for creating web apps from Python scripts.
Googletrans: Python wrapper for Google Translate API.
gTTS (Google Text-to-Speech): A library and CLI tool to interface with Google Text-to-Speech API for speech synthesis.
vbnet
Copy code

This `README.md` gives a clear explanation of the app's purpose, how to run it, and its features. You can modify it further based on any specific details or changes you make in your app.





