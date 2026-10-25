# Multimodal Stress Detection System

A Python-based project that estimates potential stress indicators by combining facial emotion analysis, voice-based sentiment analysis, and manually entered heart-rate information.

## Features

- **Facial Emotion Analysis:** Uses DeepFace to analyze facial expressions through a webcam.
- **Voice Analysis:** Converts spoken words into text using speech recognition.
- **Sentiment Analysis:** Uses TextBlob to analyze the sentiment of recognized speech.
- **Heart-Rate Input:** Allows users to enter their heart rate manually.
- **Combined Stress Indicator:** Combines facial, voice, and pulse-related scores to estimate an overall stress level.
- **Live Camera Display:** Displays facial analysis results and input status in real time.
- **CSV Reports:** Saves analysis results to a CSV file for future reference.

## Technologies Used

- Python
- OpenCV
- DeepFace
- SpeechRecognition
- TextBlob
- NumPy
- pyttsx3
- CSV

## Requirements

- Python installed on your computer
- Webcam
- Microphone
- Internet connection for Google's speech recognition service

## Installation

**1. Clone the repository**

```bash
git clone https://github.com/Rithika-Kailasa/multimodal-stress-detection.git
```

**2. Navigate to the project directory**

```bash
cd multimodal-stress-detection
```

**3. Install the required libraries**

```bash
pip install opencv-python SpeechRecognition textblob numpy pyttsx3 deepface
```

## How to Run

Run the Python application:

```bash
python "stressdetection code.py"
```

## Controls

| Key | Function |
|---|---|
| V | Capture voice input and analyze sentiment |
| H | Enter heart-rate information manually |
| S | Save the analysis report to a CSV file |
| Q | Quit the application |

## How It Works

1. The webcam captures frames for facial emotion analysis using DeepFace.
2. The user provides voice input through a microphone.
3. Speech recognition converts the voice input into text, which TextBlob analyzes for sentiment.
4. The user manually enters their heart rate.
5. The system combines the facial, voice, and pulse-related scores into an overall stress indicator.
6. The application displays the estimated stress level and a general wellness suggestion.
7. The user can save the results in a CSV report.

## Future Improvements

- Develop a web-based interface.
- Improve the scoring method using validated data.
- Integrate automatic heart-rate measurement using a suitable sensor.
- Add charts and historical report visualization.
- Evaluate the system using appropriate datasets and performance metrics.

## Disclaimer

This project is intended for educational purposes only. It estimates potential stress indicators and is not a medical diagnostic tool. Its results should not be used to make medical decisions.

## Author

**kasula Poojitha**

GitHub: [Kasula Poojitha](https://github.com/PoojithaKasula)
