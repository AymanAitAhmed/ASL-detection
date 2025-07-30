# ASL-detection

This project demonstrates an end-to-end pipeline for **American Sign Language (ASL) recognition** using two complementary deep learning approaches:

* **I3D (Inflated 3D ConvNet)**: Captures spatiotemporal features directly from video frames.
* **ST-GCN (Spatial-Temporal Graph Convolutional Network)**: Models skeleton-based motion dynamics using human keypoints.

---

## Demo
You can see the results of the model using the following video:
https://github.com/AymanAitAhmed/ASL-detection/blob/main/annotated_video.mp4

## 📝 Project Overview

The notebook `asl_recognition.ipynb` walks through:

1. **Data Preparation**: Loading and preprocessing ASL video clips or skeleton data.
2. **Model Architectures**:

   * **I3D**: Pretrained on large-scale action recognition datasets (e.g., Kinetics), fine-tuned on ASL.
   * **ST-GCN**: Constructs a graph from pose landmark sequences and applies graph convolutions.
3. **Training & Evaluation**: Training loops, loss functions, evaluation metrics (accuracy, confusion matrix).
4. **Visualization**: Plotting training curves and qualitative results.

## 📂 Dataset Requirements

This notebook uses the ASL Citizen open source dataset

