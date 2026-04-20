# Emotion Detection Application

A web application built with IBM Watson NLP and Flask for detecting emotions in text.

## Features
- Detects emotions: anger, disgust, fear, joy, sadness
- Returns the dominant emotion
- Error handling for blank input (status 400)
- Unit tested with unittest
- Static code analysis with pylint

## Tech Stack
- Python
- Flask
- IBM Watson NLP (Emotion Predict)
- Requests

## Project Structure
```
final_project/
├── EmotionDetection/
│   ├── __init__.py
│   └── emotion_detection.py
├── templates/
│   └── index.html
├── test_emotion_detection.py
├── server.py
└── README.md
```

## How to Run
```bash
python server.py
```
Then open http://localhost:5000 in your browser.
