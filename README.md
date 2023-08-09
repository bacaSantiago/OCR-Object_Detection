# Optical Character Recognition (OCR) and Object Detection Project

This project is part of the Coursera online Specialization in Python 3 Programming by the University of Michigan. The final course in the specialization focuses on optical character recognition (OCR) and object detection in images using libraries such as Pillow, Tesseract, and OpenCV.

## Project Overview

In this project, you will work on processing a ZIP file of images containing newspaper pages. Your task is to write Python code to search through the images for specific keywords and faces. The project involves:

1. Learning how to use the `zipfile` library to extract images from a ZIP file.
2. Using OpenCV for face detection.
3. Utilizing Tesseract for optical character recognition (OCR).
4. Compositing images into contact sheets using Pillow.

## Assignment Details

- You will work with a ZIP file of newspaper images, where each page is saved as a PNG image.
- Your code should allow users to search for keywords and faces within the images.
- For each instance of a keyword match, you'll create a contact sheet of detected faces from that page.
- The project will test your ability to learn new libraries, use OpenCV for face detection, perform OCR with Tesseract, and compose contact sheets using Pillow.

## Project Structure

1. `zipExtraction(file_name)`: Extracts information (name, image, text) from a given ZIP file and stores it in a dictionary.
2. `extractFaces()`: Detects and extracts faces from images using OpenCV's face detection classifier.
3. `searchValue(value)`: Searches for a specific value (keyword) in the OCR-converted text of images and displays contact sheets of detected faces.

## Implementation Steps

1. Extract information from the provided ZIP file using the `zipfile` library.
2. Detect and extract faces from images using OpenCV's face detection classifier.
3. Perform OCR on the images using Tesseract.
4. Search for specific keywords in the OCR-converted text and display contact sheets of detected faces.

## Example Output

For instance, if you search for a specific name, your code will generate a contact sheet of all detected faces related to that name. If no faces are detected but the keyword appears in the text, you will display the corresponding page with the keyword highlighted.

## Note

The provided code snippet gives you an idea of the project's structure and functions. The actual implementation and output may vary depending on the dataset and your implementation details. Feel free to explore the code further and experiment with different images, keywords, and functionality.

Keep in mind that this project assesses your ability to combine various libraries and techniques to achieve specific image processing tasks. It's a comprehensive and challenging project that showcases your skills in Python programming and image manipulation.
