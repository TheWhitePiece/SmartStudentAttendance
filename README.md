📸 Smart Attendance System using Face Recognition

An AI-powered smart attendance system that captures a classroom photo and uses a deep learning model to identify and mark students as present or absent by comparing faces with a pre-existing dataset.

🚀 Features

🎯 Detects and identifies faces from classroom images
🗂️ Matches captured faces with existing dataset of student faces
✅ Automatically marks students as present or absent
📁 Generates attendance logs
🛠️ Tech Stack

Backend: Python
Libraries:
OpenCV
face_recognition (Dlib-based)
NumPy
Pandas
Model: made from MTCNN (Multi-task Cascaded Convolutional Neural Network) and VGGFace or VGGFace2
Data: Local folder of student face images (one image per student)
