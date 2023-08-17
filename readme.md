##Drowsiness Detection
This is a Python script that uses computer vision techniques to detect drowsiness in real-time. The script captures video from the computer’s webcam and processes each frame to detect the user’s eyes. If the user’s eyes are closed for a certain amount of time, an alarm will sound to alert the user.
##Eye Aspect Ratio (EAR)
The Eye Aspect Ratio (EAR) is a metric used to determine the state of the eyes (open or closed). It is calculated by measuring the distance between certain facial landmarks around the eyes and taking the ratio of these distances. In this script
If the EAR falls below a certain threshold, it indicates that the eyes are closed. In this script, the threshold is set to 0.25.
##Dependencies
This script requires the following libraries:

scipy
imutils
pygame
dlib
opencv-python

###You can install these dependencies by running pip install -r requirements.txt.

###To run this script, simply execute it from the command line:

      
###License
This project is licensed under the MIT License. See the LICENSE file for details.