# Colour Detection Project

This project is designed to detect and identify colors within an image or a live video feed using OpenCV, pandas, and numpy. It allows users to click on a color within an image or a video frame and displays the color name and RGB values of the clicked color.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Project Details](#project-details)

## Installation

Before running the project, ensure you have the following dependencies installed:

- Python 3.x
- OpenCV (`opencv-python`)
- pandas (`pandas`)
- numpy (`numpy`)
- imutils (`imutils`)

You can install these dependencies using pip:

>>>pip install opencv-python pandas numpy imutils


## Usage

1. **Prepare your environment**: Ensure you have Python installed on your system. If not, download and install it from the [official Python website](https://www.python.org/downloads/).

2. **Clone the repository**: Clone this repository to your local machine.

3. **Prepare your color data**: Place the CSV file containing color data (e.g., `colors.csv`) in the project directory.

4. **Run the script for image color detection**: Navigate to the project directory in your terminal or command prompt and run the script for image color detection using Python.

>>>python real_time_colour_detection.py


5. **Run the script for live video color detection**: Navigate to the project directory in your terminal or command prompt and run the script for live video color detection using Python.

>>> python live_video_color_detection.py


6. **Interact with the application**: Click on a color within the displayed image or video frame. The application will display the color name and RGB values of the clicked color.

## Contributing

Contributions are welcome! If you have a feature request, bug report, or want to improve the code, please open an issue or submit a pull request.

## Project Details

This project utilizes OpenCV for image processing and pandas for handling the color data. It provides a user-friendly interface for color detection, making it easy to identify and understand colors in images or video feeds.
