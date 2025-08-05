# Sign-Language-Converter
📌 Overview
This project presents an intelligent Bi-Communicational System designed to facilitate effective communication between hearing and speech-impaired individuals and the general public. Leveraging Machine Learning, Neural Networks, and Machine Translation, the system enables:

🗣️ Speech-to-Indian Sign Language (ISL) conversion

🤟 Indian Sign Language-to-Text translation

Our solution supports real-time, two-way communication, empowering accessibility and inclusion using technology.

🎯 Objectives
Enable seamless interaction between deaf/dumb and non-disabled individuals.

Develop a user-friendly Python-based system for real-time translation.

Train models on the Indian Sign Language dataset.

Integrate Machine Learning and Neural Network approaches for high accuracy.

⚙️ Tech Stack
Component	Description
Language	Python
Libraries	OpenCV, TensorFlow/Keras, SpeechRecognition, NumPy, etc.
ML Techniques	CNNs for gesture recognition, NLP for speech/text processing
Dataset	Indian Sign Language image/gesture dataset
Others	GUI (Tkinter/Streamlit), Real-time camera input, Audio processing

🔁 System Workflow
1. 🗣️ Speech to ISL Gesture Output
Takes live speech input via microphone

Uses Speech Recognition to convert to text

Text is mapped to corresponding ISL gestures (image or video)

2. 🤟 ISL Gesture to Text Output
Captures ISL hand signs via camera

Trained CNN model identifies the gesture

Outputs the interpreted text to screen

🧠 Key Features
🔄 Bi-directional Translation (Speech ↔ ISL)

🎯 High-Accuracy Gesture Classification

🕐 Real-Time Communication

📱 User-Friendly Interface

🇮🇳 Focus on Indian Sign Language – often underrepresented in global solutions

📊 Results
Achieved >90% accuracy on ISL gesture classification (with proper lighting and background)

Real-time speech recognition tested successfully on multiple sentence structures

Enables communication without internet (offline capabilities available)

🚀 Future Scope
Expand dataset for dynamic gestures and full ISL sentences

Add voice synthesis for ISL-to-speech

Build a mobile application version

Integrate with wearable devices (e.g., smart gloves) for gesture capture
