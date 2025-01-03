
# Attendance Management System using Face Recognition
<center> <img src = "attendence_manage.png" width = 100%>

## Overview
The **Attendance Management System** is a Python-based application that leverages face recognition technology to automate the process of tracking student attendance. This project uses OpenCV for face detection and recognition, along with a user-friendly graphical interface built with Tkinter. It includes features for capturing images for training, real-time face recognition, and managing attendance records efficiently.

---

## Features
- **Face Recognition**: Automatically recognize students' faces and mark their attendance.
- **Image Capture**: Capture and save images for training the recognition model.
- **Manual Attendance**: Option to manually fill attendance records.
- **CSV Export**: Generate attendance reports in CSV format.
- **Database Integration**: Store attendance records in a MySQL database.

---

## Technologies Used
- **Python**
- **OpenCV**
- **Tkinter**
- **NumPy**
- **Pandas**
- **MySQL**
- **Pillow**

---

## Installation

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/attendance-management-system.git
cd attendance-management-system
```

### 2. Install Required Packages
Ensure Python is installed on your system, then install the necessary dependencies:
```bash
pip install -r requirements.txt
```

### 3. Set Up MySQL Database
- Create a MySQL database to store attendance records.
- Update the database connection details in the code as needed.
---

## Usage

### 1. Capture Images
- Run `main_Run.py` to open the GUI.
- Enter the student's enrollment number and name.
- Click on **"Take Images"** to capture their face images.

### 2. Train the Model
- After capturing images, click on **"Train Images"** to train the face recognition model.

### 3. Automatic Attendance
- Select **"Automatic Attendance"** to start the face recognition process using the webcam.

### 4. Manual Attendance
- Use the **"Manually Fill Attendance"** option to manually fill attendance records.

### 5. View Registered Students
- Access the admin panel to view the list of registered students and their details.

---

## Directory Structure
```plaintext
Attendance Management System using Face Recognition/
│
├── TrainingImage/               # Directory to store training images
├── TrainingImageLabel/          # Directory to save trained model
├── StudentDetails/              # Directory to save student details CSV
├── Attendance/                  # Directory to save attendance records
├── haarcascade_frontalface_default.xml  # Haarcascade file for face detection
├── requirements.txt             # Required Python packages
├── main_Run.py                  # Main application file
├── training.py                  # Script for training the face recognition model
├── testing.py                   # Script for testing face recognition
├── mini_app.py                  # Simple GUI application for capturing images
├── app.py                       # Streamlit app for attendance visualization
└── README.md                    # Project documentation
```

---

## Contributing
Contributions are welcome! If you have suggestions for improvements or additional features, feel free to fork the repository and submit a pull request.

---
## Author

- [@sandipanrakshit34](https://github.com/sandipanrakshit34)

##

---

## Acknowledgments
Special thanks to the following:
- **OpenCV** for face detection and recognition functionalities.
- **Tkinter** for GUI development.
- **NumPy** and **Pandas** for data manipulation and analysis.
- **MySQL** for database management.

---

For any questions or issues, feel free to contact **[your email]**.
