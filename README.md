# Face Recognition Based Attendance System

This is a simple face recognition-based attendance system implemented in Python using the tkinter GUI library and OpenCV. The system allows you to register new students, take their images, and then use face recognition to mark their attendance.

## Features

- Register new students by providing their ID and name.
- Capture multiple images of each student for better recognition accuracy.
- Save student profiles with their ID and name.
- Take attendance by recognizing registered students' faces.
- Display attendance records in a user-friendly table format.

## Prerequisites

Before running the application, ensure you have the following dependencies installed:

- Python 3.x
- OpenCV (`cv2`)
- tkinter
- pandas
- numpy
- Pillow (`PIL`)

You can install the required packages using pip:

```bash
pip install opencv-python-headless pillow pandas numpy

Usage:
Run the AttendanceSystem.py script to start the application.

You can perform the following actions within the application:
Register New Students: Enter the student's ID and name and click the "Take Images" button to capture their photos.

Save Student Profiles: After capturing images, click the "Save Profile" button to save the student's profile.

Take Attendance: Click the "Take Attendance" button to start recognizing students' faces and mark their attendance.

Attendance records are displayed in a table format on the right side of the application.

Additional Information:
The application uses LBPH (Local Binary Pattern Histograms) for face recognition. You can replace the face recognition model if needed.

The captured images are stored in the TrainingImage folder, and student profiles are saved in the StudentDetails\StudentDetails.csv file.

You can change the application's password by clicking the "Change Password" option in the menu.

Support
For any questions or issues, please contact us at anshika2021shukla@gmail.com.

Feel free to contribute to this project by creating pull requests or reporting bugs.

Enjoy using the Face Recognition Based Attendance System!

