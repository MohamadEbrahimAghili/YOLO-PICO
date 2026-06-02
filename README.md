# YOLO-PICO
<div align="center">
  <img src="https://github.com/user-attachments/assets/16d252c0-3591-4848-a139-61f65c33acc3" alt="parameter plot - 2">
</div>

<br>

<div align="center">
  <a href="https://colab.research.google.com/drive/1PLhdnO9PGKNKWnuW2a9lpR2wEp0FhONT?usp=sharing">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab" width="200">
  </a>
</div>

<br>

YOLO-PICO is an innovative, lightweight model designed specifically for recognizing small objects in remote sensing (RS) imagery. By addressing the unique challenges of RS data—including variable scales, orientations, environmental influences, occlusion, and diverse lighting conditions—YOLO-PICO achieves a compelling balance of localization accuracy, recognition performance, and fast inference speeds.

## Quick Start
I have provided a Google Colab notebook to make running and testing YOLO-PICO as easy and rapid as possible. There is no need for manual local installation or dependency management. 

Simply click the badge below to open the notebook, connect to a free GPU, and run the proposed paper's code in your browser:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1PLhdnO9PGKNKWnuW2a9lpR2wEp0FhONT?usp=sharing)

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

## Citation

If you find YOLO-PICO useful in your research, please consider citing our paper:

**Plain Text:**
> M. E. Aghili, H. Ghassemian, and M. Imani, "YOLO-PICO: Lightweight object recognition in remote sensing images using expansion attention modules," *Pattern Recognition*, vol. 176, p. 113114, 2026. doi: [10.1016/j.patcog.2026.113114](https://doi.org/10.1016/j.patcog.2026.113114)

**BibTeX:**
```bibtex
@article{aghili2026yolopico,
  title={YOLO-PICO: Lightweight object recognition in remote sensing images using expansion attention modules},
  author={Aghili, Mohamad Ebrahim and Ghassemian, Hassan and Imani, Maryam},
  journal={Pattern Recognition},
  volume={176},
  pages={113114},
  year={2026},
  publisher={Elsevier},
  doi={10.1016/j.patcog.2026.113114}
}

