**Image Enhancement Web Application:**
This is a simple and efficient web-based image enhancement tool built using Streamlit, OpenCV, and NumPy. The application allows users to upload an image and view a series of transformations including resizing, 
grayscale conversion, edge detection, sharpening, and contrast enhancement.

**Features**
Upload and preview JPEG image files.
Resize the uploaded image to a standard resolution (800x600).
Convert the image to grayscale.
Apply **Canny edge detection**.
Sharpen the image using a convolution kernel.
Enhance contrast and brightness using custom parameters.


View the final enhanced image with all transformations applied.

**Tech Stack**
Streamlit: For building the web interface.
OpenCV: For image processing operations.
NumPy: For efficient array manipulation.

**How It Works**
Image Upload
The user uploads a .jpg image file through the interface.
Image Processing Pipeline
The image is decoded using OpenCV.
It is resized to 800x600 pixels.
Converted to grayscale for further processing.
Edges are detected using the Canny algorithm.
A sharpening filter is applied to enhance image clarity.
Brightness and contrast are increased using scaling parameters.


**Output**
The final image is displayed with all enhancements applied.
Educational purposes to understand the effect of filters and transformations.
Prototype for more advanced computer vision applications.

**Future Improvements**
Support for more file types (PNG, BMP).
Option to download the enhanced image.
Adjustable parameters through the UI for real-time tuning.

Author
This project was developed as a part of a learning exercise in image processing and web application development.

