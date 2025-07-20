# Air-Canvas-A-Computer-Vision-Based-Drawing-System-with-SVM-Powered-ASL-Recognition

This project is an advanced Air Canvas system developed using Python, OpenCV, MediaPipe, and Machine Learning which includes Support Vector Machine techniques. It enables users to draw in the air using hand gestures, without touching any screen or surface. Designed as an interactive, touchless virtual drawing tool, this project also supports ASL sign-to-text recognition and can interpret gestures to draw shapes and objects automatically. 


🔧 Prerequisites
Ensure the following are installed:

Python 3.7+
pip (Python package installer)
Git (to clone the repository)


🧠 Libraries Required
Install dependencies by running:
pip install opencv-python mediapipe numpy pyttsx3 scikit-learn



🚀 Features:

🎯 Real-time Hand Tracking using MediaPipe

🖐️ Gesture-Based Drawing System:

Finger tracking to draw freehand

Gesture controls for mode switching (draw, erase, clear, undo, etc.)


🧠 Sign Language Recognition using SVM: 

Converts ASL signs into on-screen text


✏️ Air Text Writing: 

Write words in the air letter by letter

Recognizes individual letters to form text dynamically



🔊 Voice Feedback: 

Speaks out recognized text or shapes

Confirms tool selection or action execution via audio



🛠️ Customizable Drawing Toolkit: 

Adjustable brush colors, thickness, and tool modes

Shape detection (circle, rectangle, triangle)



📉 Smoother Drawing: 

Fingertip noise reduced using Exponential Moving Average (EMA) filter



🎨 Interactive Toolbar: 

Gesture-based access to tools and options



📦 Modular Architecture with easy-to-modify components

🔍 Noise Reduction via Exponential Moving Average filter

⚙️ Extendable System for adding more gestures, signs, and automation

Visual feedback and real-time updates



📹 How It Works

Opens webcam feed.

Detects and tracks hand landmarks.

Recognizes specific gestures using an SVM model.

Draws corresponding output on the virtual canvas.




📝 Notes

Make sure your webcam is enabled.

The SVM model should be trained beforehand.
