Sign Language Recognition System

A real-time sign language recognition system built with Python, OpenCV, Mediapipe, and TensorFlow/Keras. The project translates hand gestures into text (and optionally speech), helping bridge the communication gap between the hearing-impaired community and others.


✨ Features

🎥 Real-time hand gesture detection via webcam

🧠 Deep learning model (CNN/RNN) for classification

🔤 Support for alphabets / words (extendable to sentences)

🗣️ Optional text-to-speech conversion

⚡ Modular design for adding more gestures or sign languages


🛠️ Tech Stack

Python 3.x

OpenCV – image/video capture and preprocessing

Mediapipe – hand landmark detection

TensorFlow/Keras – model training and prediction

NumPy / Pandas / Matplotlib – data handling and visualization


Dataset

You can use publicly available datasets like ASL Alphabet Dataset or create your own by capturing gestures via webcam.

Place your dataset inside the data/ folder.

🔮 Future Work

Extend support to full sentences (sequence modeling with LSTMs/Transformers).

Improve accuracy with larger datasets.

Deploy as a web app or mobile app.

Add multi-language sign support.