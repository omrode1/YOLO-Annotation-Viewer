# YOLO Annotation Viewer

A Python application that allows users to visualize and validate YOLO annotations on images. This tool helps users to check the bounding boxes and class labels assigned to objects in images, ensuring the accuracy of annotations in computer vision projects.

## Features

- Load YOLO annotations and corresponding images from a specified folder.
- Display images with bounding boxes for each annotated object.
- Navigate through multiple images using the arrow keys.
- Plot class distribution of annotated objects.

## Requirements

This application requires Python 3 and the following libraries:

- `opencv-python`
- `matplotlib`
- `collections`

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/YOLO-Annotation-Viewer.git
   ```
2. Change into the project directory:
   ```bash
   cd YOLO-Annotation-Viewer
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Place your images and YOLO annotation files in a folder.
2. Ensure there is a `classes.txt` file in the same folder that contains the class names.
3. Run the application:
   ```bash
   python Validate_labels.py
   ```
4. Follow the on-screen prompts to enter the folder path and class colors.
5. Use the right and left arrow keys to navigate through the images.

## Contributing

Feel free to submit issues, fork the repository, and create pull requests if you would like to contribute!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
