
# ai-smart-doorbell
🔔AI Smart Doorbell

An AI-powered Smart Doorbell system that detects human faces in real time using a webcam and automatically rings a doorbell sound when someone is detected.

Built with **Python**, **OpenCV**, and **face_recognition**, this project demonstrates how computer vision and simple AI techniques can be used for smart home automation.

---

# ✨ Features

📷 Real-time face detection using a webcam

🔔 Automatic doorbell sound when a face is detected

⚡ Fast performance using optimized frame processing

🧵 Non-blocking audio playback using threading

🍎 Optimized for macOS (Intel, M1, M2)

🪟 Fully compatible with Windows

---

# 🛠️ Technologies Used

Python 3.11

OpenCV

face_recognition (dlib-based)

Threading

Audio playback

macOS: afplay / playsound

Windows: playsound

---

## 📂 Project Structure
AI Doorbell/
│── main.py
│── Ding-dong.wav
│── README.md
│── .gitignore

---

## ⚙️ Installation & Setup

✅ Prerequisites

Webcam (built-in or external)

Python 3.11 recommended

### 1️⃣ Install Python 3.11 (MacOS)
1️⃣ Install Python 3.11

Using Homebrew:

brew install python@3.11


Verify installation:

python3.11 --version

2️⃣ Create a Virtual Environment
python3.11 -m venv venv
source venv/bin/activate

3️⃣ Install Dependencies
pip install opencv-python face_recognition playsound


⚠️ If face_recognition fails to install, make sure Xcode Command Line Tools are installed:

xcode-select --install

4️⃣ Run the Project
python main.py

#### Install Python 3.11 (Windows)
1️⃣ Install Python 3.11

Download from:
👉 https://www.python.org/downloads/

✔️ Make sure to check:
Add Python to PATH

Verify:

python --version

2️⃣ Create a Virtual Environment
python -m venv venv
venv\Scripts\activate

3️⃣ Install Dependencies
pip install opencv-python face_recognition playsound


⚠️ Important (Windows)
If face_recognition fails:

pip install cmake
pip install dlib
pip install face_recognition


You may also need Visual Studio Build Tools:

https://visualstudio.microsoft.com/visual-cpp-build-tools/

4️⃣ Run the Project
python main.py

⛔ Stop the Program

Press q in the camera window

Or press Ctrl + C in the terminal

---

## 🚀 How It Works

Webcam captures live video frames

Frames are scanned for human faces

When a face is detected:

Doorbell sound plays once

Sound resets when no face is present

Audio plays in a separate thread to avoid lag

---

## 📌 Use Cases

Smart home doorbell systems

AI & Computer Vision learning projects

Face detection demos

Raspberry Pi / Edge AI prototypes (with modification)

---

## 📄 License

This project is open-source and available under the MIT License.
