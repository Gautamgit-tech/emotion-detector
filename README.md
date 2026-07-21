# Emotion Detector

## Project Overview
This is the final project for the **AI Application Development** course.
It is a web application that uses the **Watson NLP library** to detect
the emotions (anger, disgust, fear, joy, sadness) expressed in a given
piece of text, and identifies the dominant emotion.

## Features
- Emotion detection using Watson NLP's EmotionPredict service
- Formatted output showing scores for each emotion and the dominant emotion
- Packaged as a reusable Python package (`EmotionDetection`)
- Unit tests covering all five emotion categories
- Web deployment using Flask
- Error handling for blank/invalid input (HTTP 400)
- Static code analysis with PyLint (10/10 score)

## Project Structure
```
emotion-detector/
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
├── templates/
│   └── index.html
├── static/
├── server.py
├── test_emotion_detection.py
├── requirements.txt
└── README.md
```

## How to Run
1. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
2. Run the unit tests:
   ```
   python3 -m unittest test_emotion_detection.py
   ```
3. Start the Flask web server:
   ```
   python3 server.py
   ```
4. Open the application in a browser at `http://localhost:5000`

## Author
Final Project — Emotion Detector (AI-based web application)
