,,,,,,,,,,,,# 🎯 Face Recognition Attendance System

A smart, real-time **Face Recognition–Based Attendance System** built using **Python, Computer Vision, and Streamlit**.  
The system automatically identifies individuals through a webcam and records attendance in **daily Excel files**, ensuring accuracy, speed, and duplicate prevention.

👨‍💻 **Developed by:** **Aditya Jadhav**  
📌 **Role Focus:** Data Scientist | Machine Learning | Computer Vision  
🔗 **GitHub:** https://github.com/AdityaJadhav-ds  
🔗 **LinkedIn:** www.linkedin.com/in/aditya-jadhav-6775702b4  

---

## 🌐 Live Demo (Streamlit)

🚀 **Try the live application here:**  
👉 **https://automated-face-attendance-aditya524.streamlit.app/**

> ⚠️ **Note:**  
> - Camera access must be allowed in the browser  
> - Live demo may have limited functionality depending on device/browser permissions  

---

## 🚀 Project Overview

Manual attendance systems are slow, error-prone, and easy to manipulate.  
This project solves that problem using **face recognition** to automatically mark attendance with **zero manual input**.

The application runs as a **Streamlit web app**, captures faces via webcam, matches them against registered users, and logs attendance securely in Excel.

---

## ✨ Key Features

- 👤 Real-time face detection and recognition  
- 🎥 Live webcam feed  
- 📊 Automatic daily Excel attendance files  
- 🚫 Duplicate attendance prevention  
- ➕ Easy face registration via web interface  
- 📈 Attendance history viewer  
- 🧩 Clean and user-friendly Streamlit UI  

---

## 🛠️ Tech Stack

- Python 3.8+
- OpenCV
- dlib
- face_recognition
- Streamlit
- NumPy
- Pandas
- OpenPyXL

---

## 📂 Project Structure
face-recognition-attendance-system/
│
├── app.py # Main Streamlit application
├── face_recognition_system.py # Face recognition logic
├── attendance_manager.py # Excel attendance handling
├── setup_sample_data.py # Optional sample data generator
├── requirements.txt # Dependencies
├── README.md # Documentation
│
├── known_faces/ # Registered users
│ └── Person_Name/
│ ├── image1.jpg
│ ├── image2.jpg
│
└── attendance/ # Daily Excel attendance files
└── Attendance_YYYY-MM-DD.xlsx


---

## ⚙️ System Requirements

- Python 3.8 or higher
- Webcam
- Windows / Linux / macOS

---

## 📥 Installation

### Clone the repository
bash
git clone https://github.com/AdityaJadhav-ds/automated-face-attendance.git
cd face-recognition-attendance-system


### Install dependencies
bash
pip install -r requirements.txt


> **Note (Windows users):**  
> Installing `dlib` may require **Visual Studio Build Tools**.

---

## ▶️ Run the Application
bash
streamlit run app.py


The app will open automatically at:
text
http://localhost:8501


---

## 🧑‍💻 How to Use

### ✅ Mark Attendance
- Open the app  
- Select **Mark Attendance**  
- Allow camera access  
- Face the camera  
- Attendance is recorded automatically  

---

### ➕ Register a New Face

#### Method 1: Web Interface
- Go to **Register New Face**
- Enter the person's name
- Capture **3–5 images** from different angles
- Save

#### Method 2: Manual
text
known_faces/PersonName/

- Add clear face images  
- Restart the app  

---

## 📊 Attendance Records

Generated daily  

File format:
text
Attendance_YYYY-MM-DD.xlsx


Stored in:
text
attendance/


### Columns
- Name
- Date
- Time

---

## 🧠 Technical Details
- Face Detection: HOG-based model  
- Face Encoding: 128-dimensional embeddings  
- Matching Threshold: 0.6 (configurable)  
- Supported Formats: JPG, PNG, JPEG  

---

## 🧪 Tips for Best Accuracy
- Ensure good lighting  
- Register multiple face angles  
- Use clear, high-quality images  
- Avoid face obstructions (masks, sunglasses)  

---

## 🐞 Troubleshooting

### Camera Not Working
- Check webcam connection  
- Close other camera-using apps  
- Allow browser camera permission  

### Face Not Recognized
- Improve lighting  
- Register more images  
- Face the camera directly  

### Dependency Issues
text
dlib error → install Visual Studio Build Tools
OpenCV issue → try opencv-python-headless


---

## 📜 License
This project is open-source and free to use for educational and commercial purposes.

---

## 🤝 Contact

**Aditya Jadhav**  
📌 Open to Data Science & ML roles  
🔗 GitHub: https://github.com/AdityaJadhav-ds  
🔗 LinkedIn: https://www.linkedin.com/in/aditya-jadhav-6775702b4  

⭐ If you find this project useful, consider giving it a **star**!
