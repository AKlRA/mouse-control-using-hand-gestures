#  Hand Gesture Mouse Control

This project uses computer vision to control mouse actions using hand gestures. The program captures video input, detects hand landmarks, and interprets gestures to perform mouse actions such as moving the cursor, left click, right click, double click, and taking screenshots.


## Requirements  
Python 3.x   
OpenCV (cv2)   
MediaPipe (mediapipe)   
PyAutoGUI (pyautogui)   
Pynput (pynput)   
Utilities (util)   


## Installation

Install the required packages using pip:    **pip install opencv-python mediapipe pyautogui pynput**  
 Ensure the util module is available in your project, which contains helper functions such as get_angle and get_distance.

## Usage  

Run the main() function to start the program:  
  
## How It Works

Hand Detection: Uses MediaPipe's hand detection model to locate hand landmarks in real-time.  
Gesture Recognition: Interprets hand gestures by analyzing the angles and distances between landmarks.  
Mouse Control: Translates recognized gestures into mouse actions using PyAutoGUI and Pynput.  
  
## Gestures

Move Mouse: Move your index finger to control the mouse cursor.  
Left Click: Specific gesture detected by angles between landmarks.  
Right Click: Specific gesture detected by angles between landmarks.  
Double Click: Specific gesture detected by angles between landmarks.  
Screenshot: Specific gesture detected by angles between landmarks.  

## License

This project is licensed under the MIT License.
