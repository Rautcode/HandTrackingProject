# Hand Tracking Project

This project uses **OpenCV**, **Mediapipe**, and **PyAutoGUI** to implement a hand tracking system that can control the mouse, adjust volume, and perform various interactions based on hand gestures.

## Features
- **Hand Detection**: Detects hand movements using Mediapipe.
- **Mouse Control**: Moves the cursor using hand gestures.
- **Click & Scroll**: Left-click, right-click, and scroll using hand movements.
- **Volume Control**: Adjusts the system volume using gestures.
- **Frame Rate Display**: Shows real-time FPS on the screen.

## Installation

### Prerequisites
Ensure you have Python installed. Then install the required dependencies:
```sh
pip install opencv-python mediapipe pyautogui pynput numpy pyttsx3
```

## Usage
Run the `main.py` file:
```sh
python main.py
```

### Gesture Controls
- **Index Finger Up** → Move Cursor
- **Index + Middle Finger Up** → Click
- **Thumb + Index Finger Pinch** → Adjust Volume
- **All Fingers Up** → Scroll Down
- **Four Fingers Up (excluding thumb)** → Scroll Up
- **Three Fingers Up** → Double Click

## Files
- **`HandTrakingModule.py`**: Contains the hand tracking logic.
- **`main.py`**: Main script that implements gesture-based controls.


## Contributing
Feel free to fork this repository and contribute by submitting pull requests.

## License
This project is licensed under the MIT License.
