# Live-Volume-control
The code captures video, flips the frame, and processes it with MediaPipe Hands to detect hand landmarks. It draws the landmarks, measures the distance between the thumb and index finger, and adjusts the screen brightness based on this distance. The live video is displayed until 'p' is pressed.This Euclidean Distance is calculated by the math library called hypot.
Futhermore that distance is transformed between the range of 0-100 via the usage of np.interp

# NOTE: To run this you must install requirements.txt and have python version >= 3.10

