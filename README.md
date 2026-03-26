# 🧠 Face Recognition Attendance System

A desktop application that uses facial recognition to automate user authentication and attendance tracking in real time.  
This project demonstrates the integration of computer vision with a simple user interface to create a functional and practical system for identity verification.

---

## 🚀 Features

- 🎥 Real-time face detection using webcam  
- 🧠 Face recognition with pre-registered users  
- ➕ New user registration via camera capture  
- 🔐 Login system based on facial identity  
- 📝 Attendance logging with timestamps  
- 🖥️ Simple GUI built with Tkinter  

---

## 🛠️ Technologies Used

- **Python**
- **OpenCV** (Computer Vision)
- **face_recognition** (Facial Recognition)
- **Tkinter** (GUI)
- **Pillow** (Image processing)

---

## 📂 Project Structure

```
face-recognition-attendance/
│
├── main.py               # Main application logic
├── util.py               # Helper functions (UI components, utilities)
├── db/                   # Stored user face images
├── .log.txt              # Attendance logs
├── requirements.txt      # Dependencies
├── requirements_windows.txt  # Dependencies (Windows)
└── README.md
```

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/your-username/face-recognition-attendance.git
cd face-recognition-attendance
```

### 2. Install dependencies

**Linux / macOS:**
```bash
pip install -r requirements.txt
```

**Windows:**
```bash
pip install -r requirements_windows.txt
```

### 3. Run the application

```bash
python main.py
```

---

## 📌 How It Works

1. The system captures video from the webcam  
2. Faces are detected and compared with stored images in the `db/` folder  
3. If a match is found → user is authenticated  
4. Attendance is logged with a timestamp in `.log.txt`  
5. New users can be registered through the interface  

---

## 📈 Learning Outcomes

- Applied computer vision techniques in a real-world use case  
- Integrated facial recognition into a working application  
- Built a desktop GUI with Tkinter  
- Managed file-based data storage for user recognition  
- Improved understanding of real-time processing and system flow  

---

## ⚠️ Limitations

- Accuracy depends on lighting conditions and image quality  
- No database integration (file-based storage only)  
- Basic UI (can be improved with modern frameworks)  

---

## 🚀 Future Improvements

- Integrate a database (PostgreSQL / MongoDB)  
- Add a web-based interface (Spring Boot + Angular)  
- Improve recognition accuracy and performance  
- Deploy as a cloud-based service
