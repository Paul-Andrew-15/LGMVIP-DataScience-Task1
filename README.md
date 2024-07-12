# LGMVIP-DataScience-Task1
## Image to Pencil Sketch with Python
The project "Image to Pencil Sketch with Python" involves transforming a color image into a pencil sketch using image processing techniques. Here's a brief description of the steps involved:

1. Read Image in RGB Format: Load an image file in its original RGB (Red, Green, Blue) format.

2. Convert to Grayscale: Convert the RGB image to a grayscale image. Grayscale images use a single channel to represent intensity, simplifying subsequent processing.

3. Invert Grayscale Image: Invert the grayscale image to obtain a negative image. Inversion enhances certain details and prepares the image for the pencil sketch effect.

4. Create Pencil Sketch Effect: Combine the grayscale image with the inverted version using a simple mathematical operation (division). This step blends the details from the inverted image with the structure of the grayscale image, mimicking the appearance of a pencil sketch.

5. Implementation Using OpenCV: Utilize OpenCV, a popular library for computer vision tasks in Python, to handle image loading, conversion, inversion, and blending. OpenCV provides efficient functions for manipulating images as arrays, making it suitable for this project.

This approach leverages basic image processing techniques to achieve a visually appealing pencil sketch effect programmatically.
