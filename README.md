# Real-Time Face Recognition Attendance System

The Real-Time Face Recognition Attendance System is an automated solution for attendance tracking that utilizes YOLOv8 for face detection and the face_recognition library for identifying individuals. This system marks attendance by matching detected faces with known images and records presence in a CSV file, making it ideal for use in schools and workplaces.

## Steps to run the project:

1) Create a virtual environment using `py -m venv env`
2) Activate the virtual environment using `env\Scripts\activate`
3) Before installing the requirements, install dlib separately using `pip install "dlib_file_path"`
4) Install the requirements using `pip install -r requirements.txt`
5) Run the project using `streamlit run image_attendance.py` for image input (or) `streamlit run video_attendance.py` for video input.