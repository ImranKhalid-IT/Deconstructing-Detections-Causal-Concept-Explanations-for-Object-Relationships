# YOLOv5/Faster RCNN Object Detection Explanation & Visualization

This repository provides a framework to run object detection on images using YOLOv5 and generate explainable visualizations for selected objects. The code supports batch analysis for figures, as well as optional tables and single-example explanations.  

## Features

- **YOLOv5 Object Detection**
  - Uses `yolov5x6` model for high-accuracy detection
  - Detects multiple objects in uploaded images

- **Explainable Visualizations**
  - Generate multi-example figures (e.g., Figure 5) for object detection results
  - Configurable object classes for analysis
  - Optional single-example explanations and table generation

- **Flexible Execution**
  - Users can choose which analysis to run via simple flags
  - Supports multiple images in batch processing

## Installation

Clone the repository and install dependencies:

```bash
git clone <repository_url>
cd <repository_folder>
pip install torch torchvision matplotlib numpy opencv-python
Contact

Muhammad Imran
Email: <imran.khalid292@gmail.com>
