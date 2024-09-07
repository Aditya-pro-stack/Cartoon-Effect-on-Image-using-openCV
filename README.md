# Cartoonify Image using OpenCV

## Project Overview
This project implements a cartoonification process using OpenCV to transform an input image into a cartoon-like output. The project is developed in Python and runs in Google Colab, leveraging image processing techniques like edge detection, color quantization, and noise reduction to achieve the cartoon effect.

## Features
- **Edge Detection:** Generates an edge mask to highlight the main contours in the image.
- **Color Quantization:** Reduces the image's color palette using K-Means clustering to give a cartoonish appearance.
- **Noise Reduction:** Applies a bilateral filter to smooth the image while preserving edges.
- **Cartoonification:** Combines the edge mask and the quantized image to produce the final cartoonified result.

## Technologies Used
- Python
- OpenCV
- NumPy
- Matplotlib

## Project Workflow
1. **Load Image:** The project reads and displays the original image using OpenCV and Matplotlib.
2. **Edge Mask Creation:** A grayscale image is processed to detect edges using adaptive thresholding.
3. **Color Quantization:** K-Means clustering is applied to reduce the color palette of the image.
4. **Noise Reduction:** A bilateral filter smooths the image, removing unwanted noise while keeping the edges sharp.
5. **Cartoonification:** The edge mask is combined with the quantized image to produce the final cartoon effect.

## How to Run the Project
1. Clone or download the repository.
2. Upload the project notebook to Google Colab.
3. Upload your own image or use the provided sample image.
4. Run the cells step-by-step to cartoonify the image.
