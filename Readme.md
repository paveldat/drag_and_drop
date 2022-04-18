# Drag and Drop
In this project I am going to learn how to create a virtual drag and drop system using opencv and python

## Features
* Can track your hand in real-time
* Can change your computer's volume based on your hand activity

## How to install
1. Clone this repository on your computer
`https://github.com/paveldat/drag_and_drop.git`
2. Install all the requirements
`run libraries.bat`
Or
`pip install -r requirements.txt`
3. Run the program
`python main.py`

## Help
You might face issue with webcam not showing and you get errors.
To solve it just change the value in this line (for example to `1`).
`cap = cv2.VideoCapture(0)`
Increment this number until you see your webcam.

## Hand Landmarks
<img src="https://github.com/paveldat/gesture_volume_control_v2/blob/main/img/HandLandmarks.png">


## Result
![Alt Text](https://github.com/paveldat/drag_and_drop/blob/main/img/result.gif)