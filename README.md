# FashionFlux: Pose Estimation for Virtual Try-On

FashionFlux is an innovative virtual try-on platform that leverages cutting-edge AI technologies to revolutionize the online shopping experience. This repository focuses on the **Pose Estimation** module, a critical component of the FashionFlux system, enabling accurate garment overlay and dynamic fit simulation based on user posture.

## Overview

The **Pose Estimation** module is designed to detect and track keypoints of the human body, enabling garments to adapt naturally to different user postures. By integrating this module with other components of FashionFlux, users can visualize how clothing items fit and look on them in real-time.

### Key Objectives
- Detect and track human body keypoints with high accuracy.
- Enable dynamic garment overlay that conforms to user posture.
- Provide a seamless and interactive virtual try-on experience.


## Features

- **Real-Time Pose Estimation**: Uses the MediaPipe library for detecting and tracking body keypoints efficiently.
- **Dynamic Fit Simulation**: Ensures garments adapt naturally to user posture and body shape.
- **High Accuracy**: Achieves pose alignment accuracy of ~85–90% based on keypoint matching.
- **Scalable Architecture**: Designed to handle high volumes of concurrent users without compromising performance.


## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/iam-ajeetsingh/FashionFlux-PoseEstimation.git
   cd FashionFlux-PoseEstimation

2. Create a virtual environment and activate it:
   ```bash
   python3 -m venv venv
   source venv/bin/activate

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt

## Usage

1. Upload an image of a person.
2. The system detects body keypoints using the MediaPipe library.
3. Visualize the Pose of the given image.

## Sample Skeleton Pose Output Images for the corresponding input images 

![New](https://github.com/user-attachments/assets/b3f8ba4c-be4c-48f9-a8c5-8c92d7f3efd4)


Feel free to explore, use, and contribute to this project.



   
