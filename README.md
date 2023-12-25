# Real-time-photo-capturing
Capturing the photo in real time using Opencv in few lines of code as below-

Initially-
Open a webcam using cv2.VideoCapture.
Create and resize a named window for displaying frames.

Capture and Display Loop-
Continuously capture frames from the webcam.
Display each frame in a window titled "Press Space to take a Photo"(or any other).

Check for key presses-
If the Esc key is pressed, exit the loop and close the program.
If the Tab key is pressed, print a message and increment the image counter.

Release-
Release the webcam using cam.release().
Close all OpenCV windows using cv2.destroyAllWindows()
