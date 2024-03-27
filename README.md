# Object Detection with TensorFlow Hub

This repository contains code for performing object detection using TensorFlow Hub. The code utilizes a pre-trained model from TensorFlow Hub to detect objects in images provided via URLs. It employs TensorFlow for running inference, downloading images, and visualization.

## Prerequisites

- Python 3.x
- TensorFlow
- TensorFlow Hub
- Matplotlib
- PIL (Python Imaging Library)

Install the required libraries using pip:

```bash
pip install tensorflow tensorflow-hub matplotlib Pillow
```

## Usage
Running Detection on Single Image:
To detect objects in a single image, execute the following command:

```bash

python single_image_detection.py
```
This script will download an image from a specified URL, perform object detection on it, and display the image with detected objects.

Running Detection on Multiple Images:
To detect objects in multiple images, update the image_urls list in the ObjectDetaction.ipynb script with the URLs of the images you want to process. Then, execute the following command:

```bash
python multiple_images_detection.py
```
This script will download and process each image in the image_urls list and display the images with detected objects.

## Customization
You can customize the code to suit your specific requirements. For example:

Modify the model used for object detection by changing the TensorFlow Hub module.
Adjust the image dimensions for resizing.
Change the visualization parameters such as font size, box thickness, etc.

## References
TensorFlow: https://www.tensorflow.org/
TensorFlow Hub: https://www.tensorflow.org/hub
Matplotlib: https://matplotlib.org/
PIL (Python Imaging Library): https://pillow.readthedocs.io/
