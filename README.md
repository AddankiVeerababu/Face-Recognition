
🎯 **Face Recognition and Attendance System **

This project is a real-time face recognition system that automatically marks attendance by detecting and identifying faces from a webcam feed or image input. It uses face encoding techniques to match known faces and log attendance into a CSV file.

---

📝 **Project Summary**

Face recognition is one of the most popular applications of computer vision. In this project, we implement a system that captures images, detects faces, encodes their features, and compares them with a known database to identify individuals. When a match is found, the system logs the person's name along with the timestamp in an `Attendance.csv` file.

---

📌 **Key Modules & Functionality**

### 1. 🧠 Face Encoding

- Extracts facial features from reference images using the `face_recognition` library.
- Generates a unique face encoding vector for each known face.
- Stores these encodings for comparison with new inputs.

### 2. ✅ Attendance Module

- Captures input from webcam or image.
- Detects and locates faces using `OpenCV`.
- Encodes detected faces and compares with known encodings.
- If a match is found, marks attendance with name and timestamp in `Attendance.csv`.
- Resizes images and draws face boxes in color for visualization.

### 3. 🖥️ Output

## output:
![3](https://user-images.githubusercontent.com/84769073/170863303-d577cbe0-7088-4f37-aeff-f2a6527657c8.png)
---

📁 **Project Structure**

```bash
├── main.py                   # Main script to run face recognition
├── requirements.txt          # List of Python dependencies
├── Attendance.csv            # Auto-generated attendance log
├── known_faces/              # Folder containing reference images
└── README.md                 # Project documentation
