# 🖐️ Gesture Control System

Control your PC with hand gestures and voice commands — no mouse, no keyboard.

## ✨ Features
- 🤏 **Pinch** — Control volume or brightness
- ✊ **Fist** — Mute/unmute
- ✌️ **Peace sign** — Play/pause media
- 🗣️ **Voice commands** — Say "volume" or "brightness" to switch modes

## 🛠️ Tech Stack
- Python 3.11
- OpenCV
- MediaPipe
- pycaw
- SpeechRecognition

## 📁 Project Structure
```
gesture-control/
├── main.py             # Entry point
├── hand_tracker.py     # Hand detection and gesture recognition
├── volume_control.py   # Audio control
├── brightness_control.py # Screen brightness control
├── media_control.py    # Play/pause media
├── voice_control.py    # Voice command recognition
└── utils.py            # Helper functions
```

## 🚀 How to Run
```bash
pip install opencv-python mediapipe pycaw comtypes numpy SpeechRecognition pyaudio screen-brightness-control pyautogui
python main.py
```

## 💡 Motivation
Built to make PC control more accessible and intuitive using just a webcam and microphone.

## 👨‍💻 Author
Gurneev Singh | Age 16 | Built in 2 days
