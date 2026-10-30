# Emotion Detector (oaqjp-final-project-emb-ai)

An AI-based web application built with Flask and the Watson NLP library that
detects anger, disgust, fear, joy and sadness in text and reports the dominant emotion.

## Structure
- `EmotionDetection/` – package with `emotion_detector()` (handles 400 errors)
- `server.py` – Flask deployment, route `/emotionDetector`
- `test_emotion_detection.py` – unit tests
- `templates/`, `static/` – web UI

## Run
```
pip install flask requests pylint
python3.11 server.py
python3.11 -m unittest test_emotion_detection.py
pylint server.py
```
