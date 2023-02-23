# fingerpose

Finger gesture classifier for multiple hand landmarks detected by MediaPipe Handpose Detection. It detects gestures like "Victory" v or "Thumbs Up" +1 from both individual hands inside a source image or video stream. You can define additional hand gestures using simple gesture descriptions.

## How it works

Gesture detection works in three steps:

    Detect the hands' landmarks inside the video picture
    Estimating the direction and curl of each individual finger
    Comparing the result to a set of gesture descriptions

Step (1) is performed by MediaPipe Handpose, and Steps (2) and (3) are handled by this library.

Demo

Basic example

A basic working example can be found inside the dist folder. This example also includes debugging output which can be useful when you are creating your own gestures.

## Rock, Paper, Scissors game

A simple Rock, Scissors, Paper game that shows how to integrate this library into a real-world project.
