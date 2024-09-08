# Object-Detection-in-Images-using-YOLO

## Overview

This Jupyter Notebook demonstrates the implementation of object detection using the YOLO (You Only Look Once) deep learning model. YOLO is a real-time object detection system capable of detecting multiple objects within an image or video stream. This notebook provides step-by-step instructions to load a pre-trained YOLO model, process images, and identify objects within those images.

## Features

- **Loading YOLO Model:** This notebook explains how to load the YOLOv3 model along with its configuration and weights files.
- **Image Preprocessing:** The notebook includes a section on image preprocessing, where the input image is resized, normalized, and converted into a blob for YOLO.
- **Object Detection:** It covers the process of detecting objects within an image, including extracting bounding boxes, confidence scores, and class labels.
- **Post-Processing:** The notebook includes post-processing steps such as applying non-max suppression (NMS) to filter overlapping boxes and enhance detection accuracy.
- **Visualization:** The final step involves visualizing the detected objects by drawing bounding boxes and labels on the image.

## Requirements

- Python 3.x
- OpenCV
- NumPy
- Matplotlib
- YOLOv3 weights and configuration files (`yolov3.weights`, `yolov3.cfg`)

## Usage

1. **Clone the Repository:** Clone this repository to your local machine.
2. **Download YOLO Weights:** Ensure you have the YOLOv3 weights file (`yolov3.weights`) and configuration file (`yolov3.cfg`).
3. **Run the Notebook:** Open the notebook in Jupyter and run each cell sequentially. Ensure that the necessary libraries are installed.

## Important Sections

- **Loading the YOLO Model:** Detailed steps on how to load the YOLO model and set up the required files.
- **Processing Images:** Steps to preprocess images before feeding them to the YOLO model.
- **Detection Logic:** Explanation of the detection logic, including how to interpret the model's output.
- **Visualization:** Final step to draw bounding boxes and labels on the detected objects.


## Acknowledgments

- The YOLO model was developed by Joseph Redmon and Ali Farhadi.
- This notebook utilizes the pre-trained YOLOv3 model for demonstration purposes.

## Final Output
![Image not Available at Moment](https://github.com/Davityak03/Object-Detection-in-Images-using-YOLO/blob/main/final%20image.png)
