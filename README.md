# 🖼️ Cartoonify Image using OpenCV

Turn your real-life photos into cartoon-style images using Python and OpenCV!

## 📌 Project Description

This project applies a series of image processing techniques to transform real images into cartoon-like visuals. It uses grayscale conversion, blurring, edge detection, and bilateral filtering to produce a smooth, vibrant cartoon effect.

## ✅ Features

- 📷 Load and display an image
- ✂️ Resize image for consistent processing
- 🌑 Convert to grayscale
- 🧼 Apply median blur for noise reduction
- ✏️ Detect edges using adaptive thresholding
- 🎨 Apply bilateral filter to smooth colors
- 🧩 Combine edge mask and color to get cartoon effect
- 📊 Display original vs cartoon image using matplotlib

## 🛠️ Technologies Used

- Python 3
- OpenCV (cv2)
- NumPy
- Matplotlib

## 📁 File Structure

- `cartoonify_image.py` – Main script for cartoonifying images
- `README.md` – Project documentation

## 🧪 How It Works

1. Load the input image
2. Resize the image to a fixed width
3. Convert the image to grayscale
4. Apply median blur to reduce noise
5. Detect edges using adaptive thresholding
6. Apply bilateral filter for smooth color transitions
7. Combine the edge mask with the smoothed image
8. Display the original and cartoonified image side by side

## ▶️ How to Run

1. Install the required libraries:
