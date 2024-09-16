# Face Recognition Application

This is a face recognition application built with Python using OpenCV and Tkinter. It allows users to log in and register new users by capturing their facial images through a webcam.

## Features

- **Login**: Users can log in by recognizing their face from the webcam feed.
- **Register New User**: New users can register by capturing their face and providing a username.
- **Real-time Webcam Feed**: Displays the webcam feed in real-time.

## Requirements

- click==8.1.7
- cmake==3.17.2
- colorama==0.4.6
- dlib==19.18.0
- face-recognition==1.3.0
- face_recognition_models==0.3.0
- numpy==1.26.4
- opencv-python==4.9.0.80
- Pillow==9.2.0
- Face Recognition CLI tool (to perform face recognition, install from [face_recognition GitHub](https://github.com/ageitgey/face_recognition))

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/TOUZOUZ-Adnane/Face-Recognition.git
2. Navigate into the project directory:
   ```bash
   cd Face-Recognition
3. Create a virtual environment:
   ```bash
   python -m venv venv
4. Activate the virtual environment:
- On Windows:
   ```bash
   venv\Scripts\activate
- On macOS/Linux::
   ```bash
   source venv/bin/activate
5. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
6. Run the application:
   ```bash
   python main.py
## Directory Structure

- `main.py`: Main application script.
- `util.py`: Utility functions for creating UI elements and displaying messages.
- `assets/known/`: Directory to store registered user images.
- `assets/unknown.jpg`: Temporary file to store the captured image for login attempts.

## Code Overview

- **App Class**: The main class handling the application logic including webcam feed, login, and user registration.
- **Utility Functions**: Defined in `util.py` to create buttons, labels, and message boxes.

## Troubleshooting

- Ensure that your webcam is properly connected and accessible.
- Verify that all dependencies are correctly installed.
- If the Face Recognition CLI tool is not working, refer to its documentation for installation and usage.

## Contact

For any issues or questions, please contact me via:

- Email: [adnane.touzouz.ta@gmail.com](mailto:adnane.touzouz.ta@gmail.com)
- LinkedIn: [Adnane Touzouz](https://www.linkedin.com/in/adnane-touzouz/)

   
