# Edge Detection & Motion Sensing with OpenCV on Raspberry Pi

## Overview:
This project utilizes OpenCV on a Raspberry Pi 4 for Edge Detection & Motion Sensing. These techniques are crucial in Image Processing & Computer Vision. Edge Detection enhances visual data by highlighting features, while Motion Sensing interprets movement in image sequences.

In this project, OpenCV processes video frames on Raspberry Pi 4. Canny edge detection on grayscale frames identifies edges, while Mean Squared Error (MSE) between frames detects motion. This setup offers real-time edge & motion representation.

## Components Required:
- Raspberry Pi 4
- Raspberry Pi Camera
- SD Card 16/32 GB
- 5V, 3A DC Adapter for RPi
- LCD Display (Optional)
- Mouse & Keyboard (Optional)

## Raspberry Pi Camera Connection:
Connect the Camera Module to the Raspberry Pi 4 using the Camera Connector. Enable the Camera Module via `sudo raspi-config` in the terminal.

## Mean Squared Error (MSE) & Canny Edge Detection:
MSE measures differences between images. Canny Edge Detection is a multi-step algorithm for edge detection.

## Raspberry Pi Setup:
Install OpenCV and picamera. See the guide for OpenCV installation.

## Python Code for Edge Detection & Motion Sensing:
Refer to the provided Python code for implementation details.

## Output:
![703141C6-7B81-4A66-ABFA-10107D26E61A_1_201_a](https://github.com/Smnthjm08/Edge-Detection-Motion-Sensing-with-OpenCV-on-Raspberry-Pi/assets/119963915/92430cc7-05b1-4df2-a9c4-90778da7673d)


## Testing & Results:
After running the code, observe four windows displaying processed images: original, grayscale, compensated, and edge detection. Thonny Shell displays estimated FPS and motion detection status.

## Conclusion:
This project demonstrates integrating multiple image processing techniques using OpenCV on Raspberry Pi 4. It lays the groundwork for advanced surveillance systems operating in varying conditions, showcasing OpenCV's power and flexibility.
