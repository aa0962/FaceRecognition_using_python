#Face Recognition Attendance System
This Python script implements a simple face recognition attendance system using the face_recognition and OpenCV libraries. It captures live video from a webcam, detects faces, matches them against a predefined set of known faces, and marks attendance if recognized. Attendance records are saved in a CSV file with timestamps.

#Features

--Real-time face recognition using webcam feed.
--Attendance marking for recognized faces.
--CSV file logging attendance records with timestamps.

#Requirements

--Python 3.x
--OpenCV (pip install opencv-python)
--face_recognition (pip install face_recognition)

#Usage
1.Clone this repository:
--git clone https://github.com/your_username/face-recognition-attendance.git

2.Navigate to the cloned directory:

--cd face-recognition-attendance

3.Run the script:

--python face_recognition_attendance.py
--Press 'q' to exit the program.

#Configuration
Modify the known_face_encodings and known_face_names arrays in the script to include your own set of known faces and their corresponding names.

#License
This project is licensed under the MIT License - see the LICENSE file for details.

#Acknowledgments
Inspiration and guidance for this project were taken from various online tutorials and resources.
