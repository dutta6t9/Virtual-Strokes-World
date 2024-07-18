# Virtual-Strokes-World
 A web-based interactive canvas that utilizes machine learning and computer vision to recognize and transform
 hand-drawn sketches into editable digital vector graphics, allowing users to create and edit designs in a
 seamless and intuitive way.
 # Algorithm follows :
 Start reading the frames and convert the captured frames to HSV colour space.(Easy for colour detection) Prepare the canvas frame and put the respective ink buttons on it. Adjust the values of teh mediapipe intilization to detect one hand only. Detect teh landmarks by passing the RGB frame to the mediapipe hand detector Detect the landmarks, find the forefinger coordinates and keep storing them in the array for successive frames .(Arrays for drawing points on canvas) Finally draw the points stored in array on the frames and canvas .

Requirements: python3 , numpy , opencv, mediapipe installed on your system.

# RUN TIME LOOK LIKE YOUR COMPUTER SCREEN :-

![example_picOf_Virtual_stroke_World](https://github.com/user-attachments/assets/705ff6d9-204f-4994-b91c-431ade3bd53a)
