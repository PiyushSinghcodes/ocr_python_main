# <center>OCR with Python</center>

## Introduction
Optical Character Recognition, or OCR, is a common task in many domains. The earliest OCR systems were designed to serve the vision impaired. Its modern application, however, has extended to a far wider population. The goal of OCR is to take an input image and output raw text while maintaining the structure of the text in the image. In othere words, its end-goal is to preserve the line breaks, paragraph segmentation, and other features of the structure of the text on the page.

Workflow Overview

The OCR process in this project can be broken down into three main steps:

Image Preprocessing with PIL
Advanced Image Processing with OpenCV
Text Extraction with TesseractPY
1. Image Preprocessing with PIL
Pillow (PIL) is a popular Python Imaging Library that adds image processing capabilities to your Python interpreter. It provides extensive file format support, an efficient internal representation, and powerful image processing capabilities.

Loading the Image: The first step is to load the image into the program.
Resizing and Cropping: Resize or crop the image to focus on the area of interest.
Converting Image Modes: Convert the image to different modes (e.g., grayscale) if necessary.
Saving and Displaying the Image: Save and display the preprocessed image for verification.

