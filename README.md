Cartoon Image Stylization Web App

This web application allows users to upload images and transform them into cartoon-style artworks using advanced image processing techniques. Built with Flask and OpenCV, it offers six unique cartoonizing styles.

In this project we have build a Inage Stylization and Cartoonizer web app in Flask using Python and OpenCV. You only have to upload image you want to stylize and
select from the styles (Image enhancement, cartoon effect, pencil sketch, color pencil sketch, water color, pastel color) for transforming your image.

Features

Upload and Cartoonize: Easily upload images and apply one of six different cartoon styles.
Stylization Techniques: Includes adaptive thresholding, k-means clustering, and pencil sketch effects.
User-Friendly Interface: Simple and intuitive interface for a seamless user experience.
Secure and Efficient: Handles image uploads securely and processes images quickly.

Technologies Used

Flask: Web framework for handling requests and rendering templates.
OpenCV: Computer vision library for image processing.
NumPy: Library for numerical operations.

How to Run
Install required libraries:  pip install flask opencv-python-headless 

Create the necessary directories:  mkdir uploads cartoon_images

Run the application:  python your_script_name.py

Access the app at http://localhost:8080.

Usage:
Open the web app in your browser.
Upload an image.
Select a cartoon style.
Download the cartoonized image.
