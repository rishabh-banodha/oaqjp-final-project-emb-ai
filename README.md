# AI-Based-Emotion-Detection-Web-Application-Project
Final project for an AI-based emotion detection web application. The project uses the Watson NLP Emotion Predict endpoint, exposes the detector as a Python package, and provides a Flask web interface.

# Project structure
'''
EmotionDetection/
├── __init__.py
└── emotion_detection.py
templates/
└── index.html
test_emotion_detection.py
server.py
requirements.txt'''

# Setup and execution
python3 -m venv .venv
source .venv/bin/activate
python3 -m pip install -r requirements.txt
python3 -m unittest test_emotion_detection.py
python3 server.py


