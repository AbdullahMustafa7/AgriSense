# AgriSense
Autonomous plant disease detection and targeted treatment platform using computer vision and a remote-controlled rover.
🌿 AgriSense: Plant Vision Rover
This project implements a complete smart agriculture solution focused on early detection and precision treatment of plant diseases (specifically corn, based on the model name corn_disease_classifier.h5).

The system uses a combination of hardware and software components to simulate an autonomous agricultural robot:

AI/Vision: A TensorFlow/Keras model is used for real-time inference on a live video stream to classify plant leaves as Healthy or Diseased.

Rover Control: A Flask web server provides the Rover Remote control interface (using index.html and app_server.py), allowing a user to manually drive the unit (Forward, Stop, Turn) and monitor the AI feed.

Targeted Treatment: The system simulates precision spraying when a diseased plant is detected, providing visual confirmation on the video stream.

Embedded System Integration: The architecture includes logic for communication with an ESP32 microcontroller (as indicated by the code structure) to handle motor control and real-world execution.

Key Technologies: Python, Flask, TensorFlow/Keras, OpenCV, HTML/CSS, and ESP32 (for physical implementation).
