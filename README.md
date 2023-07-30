# Pixel Perfection Project

![photoeditor](https://github.com/Akash-Nagarajan-M/Pixel-Perfection/assets/86908101/0c33f9ac-0511-4485-bcb3-7b37db62f1c7)

Pixel Perfection is a web application built using Flask, IBM DB2, and Watson Assistant that allows users to upload, edit, collaborate, and download images. The application enables users to apply various image processing effects such as brightness, contrast, saturation, hue, sharpness, blur, sepia, and grayscale to their images. Users can also share their edited images with other registered users.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)

## Introduction

Pixel Perfection is designed as an interactive image editing and collaboration platform. It provides a user-friendly interface to edit and enhance images with real-time previews. Users can easily apply various effects and download the edited images. Additionally, they can collaborate with others by sharing images.

## Features

- User Registration: New users can register with a unique username, password, and email address.
- User Login: Registered users can log in using their credentials.
- Dashboard: Users can view and manage their uploaded images in their personalized dashboard.
- Upload Images: Users can upload images to their dashboard for editing and collaboration.
- Image Editing: Users can apply various image processing effects (brightness, contrast, saturation, hue, sharpness, blur, sepia, grayscale) using sliders.
- Collaboration: Users can share their edited images with other registered users, allowing them to collaborate.
- Image Download: Users can download the edited images in their preferred format and quality (JPEG or PNG, 1080p, 720p, or 480p).
- Logout: Users can log out from the application.

## Technologies Used

- Flask: A Python web framework used to build the application.
- IBM DB2: A database management system used to store user and image data.
- Watson Assistant: An AI-powered chatbot used for user interactions and providing assistance.
- HTML/CSS/JavaScript: Used for creating the frontend user interface.
- Python: Backend scripting language for processing and handling image operations.
- Pillow (PIL): Python Imaging Library used for image processing.
- IBM Cloud: Used to host the application.

## Installation

To run the Pixel Perfection application on your local machine, follow these steps:

1. Clone the repository: `git clone https://github.com/yourusername/pixel-perfection.git`
2. Navigate to the project directory: `cd pixel-perfection`
3. Install the required dependencies: `pip install -r requirements.txt`

## Configuration

Before running the application, you need to set up the following configurations:

1. Database Configuration: Set up an instance of IBM DB2 and create the necessary tables for user data and image storage. Update the database credentials in the `credentials.py` file.

2. IBM Watson Assistant: Create a Watson Assistant service instance and configure the required intents and responses for user interactions.

## Usage

1. Start the application server: `python app.py`
2. Open your web browser and go to `http://localhost:5000` to access the Pixel Perfection web application.
3. Register a new account or log in using existing credentials.
4. Upload images to your dashboard and apply various image processing effects.
5. Collaborate with other registered users by sharing your edited images.
6. Download the edited images in your preferred format and quality.



