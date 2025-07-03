
# ClearSpeak: Pronunciation Evaluation and Feedback System

ClearSpeak is an interactive application designed to help users improve their pronunciation by evaluating spoken words against reference text. It uses advanced speech recognition, phoneme analysis, and pitch detection to provide detailed feedback on pronunciation accuracy and fluency.


## Features

- Speech Recognition: Transcribes user speech into text using Google Speech Recognition API.
- Phoneme Analysis: Converts text into phonemes and compares them with reference phonemes to detect pronunciation errors.
- Pitch Extraction: Analyzes the pitch of recorded audio to assess tonal accuracy.
- Similarity Scoring: Calculates a similarity score between the user's speech and the reference text.
- Feedback Mechanism: Provides actionable feedback on pronunciation and highlights differences at the phoneme level.
- Interactive UI: A user-friendly interface built with Tkinter for seamless user interaction.
- Dataset Integration: Dynamically loads reference data (text and pitch) from an external dataset


## Requirements

Before running the application, ensure you have the following dependencies installed:

- Python 3.8+
- Libraries:
   * speech_recognition
   * librosa
   * pygame
   * nltk
   * pandas
   * requests
   * tkinter
- Dataset: Ensure the reference dataset (dataset2.xlsx) is placed in the project directory.
## Project Structure
```
ClearSpeak/
│
├── dataset2.xlsx         # Reference dataset containing text and pitch data
├── clearspeak.py         # Main application script
├── requirements.txt      # List of dependencies
└── README.md             # Project documentation

```
## Future Enhancements

- Multilingual Support: Add support for multiple languages and accents.
- Custom Feedback: Provide suggestions for improvement based on detected errors.
- Mobile Version: Develop a mobile app for on-the-go pronunciation training.
- Gamification: Introduce gamified elements to enhance user engagement
## Acknowledgements

 - [Google Speech Recognition API](https://pypi.org/project/SpeechRecognition/)
 - [Librosa](https://librosa.org/)
 - [CMU Pronouncing Dictionary](http://www.speech.cs.cmu.edu/cgi-bin/cmudict)
 - [StreamElements Text-to-speech](https://streamelements.com/)

