
# Human Identification using YOLO

This project, developed by **Aryan Raj**, focuses on human identification and detection using the YOLO (You Only Look Once) algorithm. YOLO is a state-of-the-art, real-time object detection system that can detect multiple objects in an image or video.

**Contact:**
- **Email:** aryanrajjpsps03@gmail.com
- **Phone:** +91 9341667873
- **GitHub:** [Aryannayra123321](https://github.com/Aryannayra123321)
- **LinkedIn:** [Aryan Raj](https://www.linkedin.com/in/aryan-raj-3a6555262/)

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [YOLO Model](#yolo-model)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The goal of this project is to accurately identify and detect humans in images or video streams using the YOLOv5 model. YOLO is known for its speed and accuracy, making it ideal for real-time detection applications. I built this project during my time at NIT Rourkela as a way to deepen my understanding of machine learning models and computer vision.

This project includes:
- Pre-trained YOLOv5 model for human detection.
- Python scripts for model inference on images and videos.
- Results visualization showing bounding boxes around detected humans.

## Features

- Real-time human detection using YOLO.
- Detection in both static images and live video feeds.
- Pre-trained YOLOv5 model for human identification.
- Easy-to-use interface for running detection on custom inputs.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Aryannayra123321/Human-Identification.git
    cd Human-Identification
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Download the pre-trained YOLOv5 model weights:
    - You can download the YOLOv5 pre-trained weights from the [YOLOv5 GitHub repository](https://github.com/ultralytics/yolov5).
    - Place the downloaded model weights in the `weights/` directory.

## Usage

1. **Detect humans in images**:
    ```bash
    python detect.py --source path/to/your/image.jpg --weights weights/best.pt
    ```

2. **Detect humans in video**:
    ```bash
    python detect.py --source path/to/your/video.mp4 --weights weights/best.pt
    ```

3. **Detect humans from a webcam feed**:
    ```bash
    python detect.py --source 0 --weights weights/best.pt
    ```

## YOLO Model

This project uses the YOLOv5 architecture, known for its fast and accurate object detection capabilities. YOLOv5 divides an image into a grid and predicts bounding boxes and class probabilities directly from full images in one evaluation.

### Model Weights

You can download pre-trained weights from [here](https://github.com/ultralytics/yolov5/releases). For human identification, this project uses COCO-pretrained weights.

## Results

Results of the detection will be displayed with bounding boxes around detected humans, showing the confidence scores for each detection.

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request for any improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
