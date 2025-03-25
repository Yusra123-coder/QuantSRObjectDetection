# QuantSRObjectDetection
# QuantSR for Object Detection

This repository contains the implementation of **QuantSR-based Low-bit Quantization** for real-time object detection models.

## 🚀 Overview
We adapted **QuantSR**, originally designed for super-resolution, to quantize weights and activations in **YOLO, SSD, and ResNet**. This method enhances edge device efficiency with minimal accuracy loss.

## 📂 Repository Structure

## 🛠 Installation
```sh
git clone https://github.com/YOUR_USERNAME/QuantSR-ObjectDetection.git
cd QuantSR-ObjectDetection
pip install -r requirements.txt
python demo.py --model yolov5 --device jetson
