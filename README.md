# Road Object Detection System using Convolutional Neural Networks (CNNs) and OpenCV

## Overview
This Python script implements a road object detection system that utilizes a Convolutional Neural Network (CNN) model for identifying objects on the road. The script captures video frames from a camera feed and detects various objects commonly found on roads, such as cars, pedestrians, traffic lights, and more, using OpenCV for video processing and the pre-trained CNN model for object classification.

## Key Concepts Used
- **Convolutional Neural Networks (CNNs)**: A deep learning model architecture designed for image classification tasks. In this script, a CNN model is trained to classify road objects based on input images.
- **OpenCV (cv2)**: An open-source computer vision and machine learning library that provides various functions for real-time image and video processing. OpenCV is used in this script for capturing video frames, image preprocessing, and drawing bounding boxes and labels on the detected objects.

## Usage
1. Ensure you have Python and the required libraries installed on your system.
2. Clone or download the repository containing the script.
3. Install the necessary Python dependencies by running:
4. Prepare a dataset of road object images categorized into classes (e.g., cars, pedestrians,traffic lights etc.).
5. Train the CNN model using the provided training data using the `train_images` and `train_labels` arrays.
6. Run the script `Road_Object_Detection-CNN.ipynb`.


## Example
Using the script, you can identify various objects on the road, such as cars, pedestrians, traffic lights, etc., in real-time through the camera feed.

## Note
- The accuracy of object detection may vary depending on factors such as lighting conditions, camera quality, and the quality of the trained model.
- Ensure the pre-trained model file ('road_object_detection_model.h5') is in the same directory as the script or specify the correct path to the model file in the code.
