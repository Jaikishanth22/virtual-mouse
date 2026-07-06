# 🖐️ AI Virtual Mouse

Control your computer using simple hand gestures using your webcam. This project uses **Computer Vision** and **MediaPipe** to detect hand landmarks and convert them into mouse actions such as cursor movement and clicking.

---

## 📌 Features

- 🖱️ Move the mouse cursor using your index finger
- 👆 Left-click using a finger pinch gesture
- ✨ Smooth cursor movement
- 📷 Real-time hand tracking
- ⚡ Lightweight and fast
- 💻 Works with a standard webcam

---

## 🛠️ Built With

- Python
- OpenCV
- MediaPipe
- NumPy
- AutoPy

---

## 📁 Project Structure

```
AI-Virtual-Mouse/
│
├── virual_mouse.py
├── HandTrackingModule.py
├── requirements.txt
├── README.md
└── .gitignore
```

> **Note:** The main file is currently named `virual_mouse.py`. You may rename it to `virtual_mouse.py` for better readability.

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/AI-Virtual-Mouse.git
cd AI-Virtual-Mouse
```

### 2. Create a virtual environment (Optional)

**Windows**

```bash
python -m venv .venv
.venv\Scripts\activate
```

**Linux / macOS**

```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

```bash
python virual_mouse.py
```

If you rename the file:

```bash
python virtual_mouse.py
```

---

## ✋ Gesture Controls

| Gesture | Action |
|---------|--------|
| ☝️ Index Finger Up | Move Cursor |
| ☝️ + ✌️ Index & Middle Finger Up | Tracking Mode |
| 🤏 Pinch Gesture | Left Click |

---

## 🧠 How It Works

1. Captures live video from the webcam.
2. Detects hand landmarks using MediaPipe.
3. Tracks the index fingertip position.
4. Maps camera coordinates to screen coordinates.
5. Smooths cursor movement for better control.
6. Detects pinch gestures to perform mouse clicks.

---

## 📦 Requirements

- Python 3.9+
- Webcam
- Windows / macOS / Linux

Python Libraries:

- OpenCV
- MediaPipe
- NumPy
- AutoPy

---

## 🚀 Future Improvements

- Right Click Gesture
- Double Click Gesture
- Scroll Gesture
- Drag & Drop
- Volume Control
- Brightness Control
- Screenshot Gesture
- Virtual Keyboard
- Multi-Monitor Support
- Custom Gesture Mapping

---

## 📸 Demo

Add screenshots or a GIF here.

```
assets/demo.gif
assets/screenshot.png
```

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push the branch
5. Open a Pull Request

---

## 👨‍💻 Author

**Jai Kishanth**

GitHub: https://github.com/your-github-username

---

## 📄 License

This project is licensed under the MIT License.

---

## ⭐ Show Your Support

If you found this project helpful, please consider giving it a ⭐ on GitHub. It helps others discover the project and motivates future improvements.
