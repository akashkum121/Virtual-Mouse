# 🖱️ Virtual Mouse using Eye Tracking

## 📌 Project Overview

**Virtual Mouse** is an AI-based system that allows users to control their computer cursor using eye movements and blinking. This project uses computer vision and facial landmark detection to replace traditional mouse input with a hands-free solution.

---

## 📸 Demo / Output

### 🖥️ Eye Tracking Cursor Movement

![Eye Tracking]([[images/eye-tracking.png](https://github.com/akashkum121/Virtual-Mouse/blob/main/OpenCV](https://github.com/akashkum121/Virtual-Mouse/blob/main/OpenCV.png))

### 👁️ Blink Detection (Click Action)

![Blink Click](images/blink-click.png)

### 🎯 Face Mesh Detection

![Face Mesh](images/face-mesh.png)

---

## 🚀 Features

* 👁️ Control mouse cursor with eye movement
* 🖱️ Blink to perform mouse click
* ⚡ Real-time tracking using webcam
* 💻 Hands-free computer interaction
* 🎯 Accurate eye landmark detection

---

## 🛠️ Technologies Used

* **Python**
* **OpenCV** – image processing
* **MediaPipe** – face mesh & eye tracking
* **PyAutoGUI** – mouse automation

---

## 📂 Project Structure

```
Virtual-Mouse/
│
├── images/
│   ├── eye-tracking.png
│   ├── blink-click.png
│   └── face-mesh.png
│
├── main.py
├── README.md
└── requirements.txt
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/virtual-mouse.git
cd virtual-mouse
```

### 2️⃣ Install Libraries

```bash
pip install opencv-python mediapipe pyautogui
```

### 3️⃣ Run Project

```bash
python main.py
```

---

## 🎯 How It Works

1. Captures video using webcam
2. Detects face using MediaPipe Face Mesh
3. Tracks eye landmarks (points 474–478)
4. Maps eye position to screen coordinates
5. Moves cursor based on eye movement
6. Detects blink to perform click

---

## 🧠 Core Concepts

* Face Landmark Detection
* Eye Tracking System
* Blink Detection Algorithm

---

## ⚠️ Limitations

* Needs proper lighting
* Camera quality affects accuracy
* Slight delay may occur

---

## 🔮 Future Improvements

* Right-click & scrolling
* Better accuracy with AI models
* Calibration system
* Gesture support

---

## 🤝 Contributing

Feel free to fork and improve this project!

---

## 👨‍💻 Author

**Akash Kumar**
📧 [your-email@example.com](mailto:your-email@example.com)
🔗 https://linkedin.com/in/akash-kumar-data
