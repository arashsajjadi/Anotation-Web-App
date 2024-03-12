# Annotation Web App

Welcome to the Annotation Web App repository!

## Introduction

Annotation Web App is a Django-based web application designed to facilitate image annotation tasks. Developed by Seyed Arash Sajjadi, a PhD student at the University of Saskatchewan in the Computer Science department, this tool is created under the supervision of Mark Eramian from the Image Lab.

This application aims to simplify the process of annotating images for various purposes such as object detection, image segmentation, or any other tasks that require marking regions of interest within images.

## Features

- **Image Annotation**: Upload images and annotate them by drawing rectangles directly on the canvas.
- **YOLO Format Support**: Save annotations in the YOLO format, commonly used for training object detection models.
- **User-Friendly Interface**: Intuitive user interface designed to streamline the annotation process.
- **Session Management**: Supports session management for user authentication and state persistence.
- **Customization**: Easily customize the application to fit specific annotation requirements or workflows.
- **Logging**: Tracks user interactions and provides detailed logging for analysis and audit purposes.

## Getting Started

To get started with Annotation Web App, follow these steps:

1. **Clone the Repository**: Clone this repository to your local machine using `git clone`.

2. **Install Dependencies**: Install the required dependencies by running `pip install -r requirements.txt`.

3. **Database Setup**: Set up the database by running `python manage.py migrate`.

4. **Run the Server**: Start the Django development server by running `python manage.py runserver`.

5. **Access the Web App**: Open your web browser and navigate to `http://localhost:8000` to access the Annotation Web App.

## Usage

1. **Upload Image**: Upload an image to the application using the provided form.

2. **Annotate Image**: Draw rectangles on the image canvas to annotate regions of interest.

3. **Save Annotations**: Save the annotated image along with the corresponding annotations.

4. **Export Annotations**: Optionally export annotations in YOLO format for further processing.

## Contributors

- **Seyed Arash Sajjadi**: PhD student at the University of Saskatchewan, Computer Science Department.
- **Mark Eramian**: Supervisor from the Image Lab at the University of Saskatchewan.

## Feedback and Support

If you encounter any issues or have suggestions for improvement, please feel free to open an issue on this repository. Your feedback is valuable and will help us enhance the Annotation Web App.

Thank you for using Annotation Web App!
