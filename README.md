# YOLOv8 Object Detection with Custom Backbones

## 📝 Project Description
This project implements **YOLOv8** with custom backbone architectures for CCTV-based vehicle detection:
- **MobileNetV2**: Lightweight backbone optimized for edge devices
- **VGG16**: High-accuracy backbone for improved detection performance

Designed for detecting cars and bikes in CCTV footage.

## ✨ Key Features
- Custom backbone integration (MobileNetV2/VGG16)
- Multi-scale feature extraction
- Channel adjustment layers
- Comprehensive training pipeline
- Visualization of predictions
- Model validation metrics
- GPU/CUDA support

## 🛠️ Requirements
- Python ≥ 3.7
- PyTorch ≥ 1.8
- `ultralytics` package
- torchvision
- matplotlib
- CUDA-enabled GPU (recommended)

## ⚙️ Installation
```bash
pip install ultralytics torch torchvision matplotlib
