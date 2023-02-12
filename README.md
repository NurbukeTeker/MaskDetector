🕵️‍♀️
# Mask Detector using OpenCV

This is a simple implementation of a mask detector using Python and OpenCV. The code uses Haar cascades to detect faces, eyes, and masks in a video stream. The presence or absence of a mask is indicated with a message displayed near the face.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You will need to have the following software installed on your system:

- Python
- OpenCV
- Haarcascade files for face, eye, and mask detection

### Installing

1. Clone the repository:

git clone https://github.com/your-username/mask-detector.git


2. Install the required libraries:

pip install opencv-python



3. Download the haarcascade files for face, eye, and mask detection and place them in the project directory.

### Running the code

Run the following command in the terminal to start the mask detector:

python mask_detector.py


The code will start a video stream using your default camera and display a window showing the video frames. If a face is detected in the frame, the code will apply Haar cascades to detect eyes and a mask. If a mask is detected, the message "Mask" will be displayed near the face. If no mask is detected, the message "No Mask" will be displayed.

## Author

[Your Name](https://github.com/your-username)

## License

This project is licensed under the [MIT License](LICENSE).

