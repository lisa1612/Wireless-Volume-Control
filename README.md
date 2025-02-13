# Wireless-Volume-Control🔊

A Python-based **Wireless Volume Control** system that allows users to adjust their computer’s volume using hand gestures, powered by **OpenCV, MediaPipe, and Pycaw**.

## Features
- Adjust system volume using hand gestures
- Utilizes OpenCV for real-time video capture
- Uses MediaPipe for hand-tracking
- Controls system audio with Pycaw

## 🛠 Installation

### Prerequisites
Ensure you have Python installed on your system. Then, install the required dependencies:

```sh
pip install opencv-python mediapipe numpy comtypes pycaw
```

## Usage

1. **Clone the Repository**

```sh
git clone https://github.com/yourusername/wireless-volume-control.git
cd wireless-volume-control
```

2. **Run the Jupyter Notebook**

Open the Jupyter Notebook and execute the code:

```sh
jupyter notebook
```

Run the provided `.ipynb` file to start gesture-based volume control.

## 🚀 How It Works
- The script captures video from the webcam
- MediaPipe detects hand landmarks
- The distance between the thumb and index finger determines volume level
- Pycaw adjusts the system volume accordingly






