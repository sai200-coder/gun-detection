------------------------------------------------------------------------------------------------------------------------

# Gun Detection System using OpenCV

This Python script utilizes OpenCV to detect guns in a video feed from a camera. It employs a pre-trained Haar cascade classifier for gun detection. 

## Prerequisites

- Python 3.x
- OpenCV (cv2)
- Numpy
- Imutils

## Installation

1. Clone this repository to your local machine:

```
git clone https://github.com/yourusername/gun-detection.git
```

2. Ensure you have all the required dependencies installed. You can install them using pip:

```
pip install opencv-python numpy imutils
```

## Usage

1. Make sure your camera is properly connected to your system.
2. Run the Python script:

```
python gun_detection.py
```

3. The script will open up a window displaying the camera feed. If any guns are detected, it will print "Guns detected" in the terminal.

4. To quit the program, press the 'q' key.

## Notes

- The script assumes the camera feed is available at index 0. If your camera is connected differently, you may need to modify the `camera = cv2.VideoCapture(0)` line accordingly.
- The gun detection is based on the Haar cascade classifier provided in the `cascade.xml` file. You may need to fine-tune the parameters or use a different cascade classifier for better accuracy depending on your use case.
- This script is intended for educational purposes and should not be used for any illegal or harmful activities.

-------------------------------------------------------------------------------------------------------------------------

