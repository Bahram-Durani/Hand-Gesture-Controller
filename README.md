## Hand Gesture Controller

Control system volume, brightness, mute, and media playback using hand gestures via your webcam.
Powered by OpenCV and MediaPipe.

Features

1. Thumb up/down → Brightness up/down
2. Index finger only (vertical swipe) → Volume up/down
3. Two fingers (index + middle) → Next track
4. Rock on (thumb + index + pinky) → Mute toggle
5. Pinch (thumb–index)
-  Right hand → Volume (0–100%)
-  Left hand → Play/Pause

6. On-screen volume bar and gesture feedback overlay
7. Works on Windows, macOS, Linux

Requirements

* Python 3.8+
* A webcam
* Packages: opencv-python, mediapipe, numpy
* OS-specific helpers (for full functionality):

* Windows: pycaw, comtypes, optional keyboard, screen-brightness-control
* macOS: brightness CLI via Homebrew
* Linux: amixer, brightnessctl, playerctl

Installation

Tip: Install with the same interpreter you will use to run the script.

Common packages (all OS)

*  pip install --upgrade pip
*   pip install opencv-python mediapipe numpy
Windows

* pip install pycaw comtypes screen-brightness-control

# optional but nice for media keys:

* python -m pip install keyboard

# brightness control tool

* brew install brightness



