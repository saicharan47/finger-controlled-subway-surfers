# Finger-Controlled Subway Surfers using Computer Vision

Control Subway Surfers using only your index finger. No keyboard. No controller. Just AI and your webcam.

This project uses real-time hand tracking to detect index finger movement and converts it into game controls.

---

## Demo

* Move finger left → Move left
* Move finger right → Move right
* Move finger up → Jump
* Move finger down → Slide

Runs in real time using webcam input.

---

## Features

* Real-time finger tracking at 30 FPS
* Uses MediaPipe hand landmark detection
* Converts finger motion into keyboard input
* Works with Subway Surfers web version
* Lightweight and runs locally
* No training required

---

## Tech Stack

* Python
* OpenCV
* MediaPipe
* pynput
* Computer Vision

---

## How It Works

1. Webcam captures video stream
2. MediaPipe detects hand landmarks
3. Index finger tip position is extracted
4. Movement direction is calculated
5. Keyboard events are triggered
6. Game responds instantly

Landmark used:

Index finger tip → Landmark ID 8

---

## Installation

Clone the repository

```
git clone https://github.com/saicharan47/finger-controlled-subway-surfers.git
```

Go to project folder

```
cd finger-controlled-subway-surfers
```

Create virtual environment

```
python -m venv venv
```

Activate environment

Windows:

```
venv\Scripts\activate
```

Install dependencies

```
pip install opencv-python mediapipe pynput
```

Run the program

```
python main.py
```

---

## Usage

1. Run the Python script
2. Open Subway Surfers in browser
3. Move your index finger to control player

Game link:

https://poki.com/en/g/subway-surfers

---

## Project Structure

```
finger-controlled-subway-surfers/
│
├── main.py
├── README.md
├── .gitignore
├── LICENSE
```

---

## Applications

* Gesture-based game control
* Accessibility tools
* Human computer interaction
* Touchless interfaces
* Computer vision research

---

## Future Improvements

* Add gesture classification model
* Improve stability using smoothing
* Add GUI interface
* Support multiple games
* Add calibration system

---

## Author

Sai Charan

GitHub:
https://github.com/saicharan47

---

## License

MIT License

---

## Star the repo

If you found this useful, consider starring the repository.
