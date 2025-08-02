# 🖱️ GesturePad: AI-Based Mouse Controller

GesturePad is a real-time gesture recognition system that uses your hand to control your mouse! Built using **Python**, **OpenCV**, and **MediaPipe**, it enhances human-computer interaction and is especially useful for accessibility and hands-free tasks.

## ✨ Features

- 📍 Real-time hand tracking using MediaPipe
- 👆 Index, middle, and thumb gesture recognition
- 🖱️ Mouse movement & click simulation
- 🚀 50% improved interaction speed for accessibility use cases


## 🛠️ Tech Stack

| Component     | Tool/Library     |
|---------------|------------------|
| Programming   | Python           |
| Vision Engine | OpenCV           |
| Hand Tracking | MediaPipe Hands  |
| Input Control | pynput, pyautogui|

## 🧠 How It Works

1. **Hand Detection**: MediaPipe detects hand landmarks.
2. **Gesture Logic**:
   - Move mouse: Index finger pointing
   - Left click: Specific finger angle + distance
   - Right click: Alternate angle + distance
3. **Cursor Control**: Translates gestures to system-level mouse actions.

## 📁 File Structure

<pre><code> ## 📁 File Structure ``` GesturePad/ ├── Vm.py # Main application logic ├── util.py # Utility functions (angle, distance) └── README.md # You're reading it! ``` </code></pre>

## 🚀 Getting Started

### 1. Clone this repo:
git clone https://github.com/H-arsha/GesturePad.git
cd GesturePad
### 2. Install dependencies:
pip install opencv-python mediapipe pyautogui pynput numpy
### 3. Run the app:
python Vm.py
Press Q to exit the app.

## 💡 Use Cases
Touch-free PC interaction
Accessibility control for differently-abled users
Gesture-based presentations or demos

## 📜 License
This project is open-source under the MIT License.



