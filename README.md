# YOLO-PICO
<div align="center">
  <img src="https://github.com/user-attachments/assets/16d252c0-3591-4848-a139-61f65c33acc3" alt="parameter plot - 2">
</div>

YOLO-PICO is an innovative, lightweight model designed specifically for recognizing small objects in remote sensing (RS) imagery. By addressing the unique challenges of RS data—including variable scales, orientations, environmental influences, occlusion, and diverse lighting conditions—YOLO-PICO achieves a compelling balance of localization accuracy, recognition performance, and fast inference speeds.

## Key Innovations

- **Expansion Attention (EA) Module**  
  Integrates spatial and spectral information to enhance the resolution of features. This module is repeatedly and optimally used across network layers, allowing the model to focus on critical details pertinent to small objects.

- **Lightweight Architecture**  
  YOLO-PICO’s architecture is tailored to be compact, reducing the parameter count significantly while still achieving performance levels comparable or superior to other lightweight models such as YOLOv3-tiny, YOLOv5n, YOLOv6n, and YOLOv8n.

- **Multi-scale Feature Extraction**  
  The design incorporates efficient multi-scale feature extraction to effectively capture the details and nuances of small objects, even in challenging RS environments.

- **Size-Normalized Average Precision (SNAP)**  
  A new evaluation metric proposed with YOLO-PICO, SNAP assesses the parameter efficiency of models, further validating its effectiveness in RS applications with constrained hardware resources.

## Features

- **Enhanced Localization Accuracy:**  
  YOLO-PICO is designed to boost the accurate localization of small objects, an essential factor in remote sensing tasks.

- **Increased Inference Speed:**  
  The compact and efficient model architecture ensures high-speed inference, making it ideal for real-time applications.

- **Low Parameter Count:**  
  Despite its small size, YOLO-PICO does not compromise on performance, making it suitable for environments with limited computational resources.

- **Robust Performance:**  
  Experiments conducted on datasets like VeDAI and NWPU-VHR-10 demonstrate that YOLO-PICO performs on par with or surpasses its lightweight competitors.

## Experimental Evaluation

YOLO-PICO has been extensively evaluated on popular remote sensing datasets:
- **VeDAI**
- **NWPU-VHR-10**

These evaluations show that YOLO-PICO not only improves recognition accuracy for small objects but also substantially reduces model size and inference time compared to its peers.

## Installation
PLEASE NOTE THAT THE CODE FOR YOLO-PICO WILL BE MADE AVAILABLE AFTER THE PAPER IS ACCEPTED.
### Requirements

- Python 3.6 or higher
- Relevant libraries (e.g., PyTorch/TensorFlow, NumPy, OpenCV, etc.)

### Setup

Clone the repository and install the necessary dependencies:

```bash
# Clone the repository
git clone https://github.com/MohamadEbrahimAghili/YOLO-PICO.git
cd YOLO-PICO-main

# Install dependencies
pip install -r requirements.txt
