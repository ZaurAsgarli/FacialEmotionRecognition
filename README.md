📸 Facial Emotion Recognition
This project uses computer vision and deep learning to detect human emotions in real-time from a webcam feed. It combines OpenCV for face detection and a Keras-based neural network model to classify emotions from facial expressions.

🎯 Features
Real-time webcam video capture

Face detection using Haar Cascade classifier

Emotion classification using a trained deep learning model

Display of detected emotions with bounding boxes

🧠 Emotions Recognized
The model classifies faces into one of the following emotions:

Angry
Happy
Neutral
Sad
Surprise

⚙️ Requirements
Make sure you have the following installed:

opencv-python 
numpy 
tensorflow

🧠 How It Works
Webcam Capture: OpenCV reads frames from your webcam.

Face Detection: A Haar cascade classifier detects faces in each frame.

Preprocessing: Each detected face is resized and converted to RGB.

Emotion Prediction: The image is passed into a deep learning model trained with Keras.

Display: The predicted emotion is displayed in a window, along with a bounding box.

📌 Notes
The model expects face images of size 224x224 and RGB format.

Make sure your camera is accessible. If the script says “Cannot open camera,” check your device settings.

