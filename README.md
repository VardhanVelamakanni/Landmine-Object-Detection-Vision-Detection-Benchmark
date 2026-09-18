<div align="center">

# Landmine Object Detection Benchmark

### A standardized cross-framework benchmark for evaluating object detection models on small-scale landmine datasets.

<p>
  <img src="https://img.shields.io/badge/IEEE-ICoECIT%202026-black"/>
  <img src="https://img.shields.io/badge/PyTorch-2.x-red"/>
  <img src="https://img.shields.io/badge/Computer%20Vision-Research-blue"/>
</p>




</div>

---

## Research Objective

This work investigates how modern object detection architectures **generalize under limited-data conditions**. Rather than proposing a new detector, this research establishes a **standardized benchmarking pipeline** to analyze the trade-offs between localization accuracy, precision, recall, and real-time inference on a **1.2K-image landmine dataset**.

---

## Methodology

- Standardized training across all models (50 epochs, identical input resolution and batch settings).
- Unified YOLO and COCO annotation workflows for reproducible evaluation.
- Multi-metric analysis using **Precision, Recall, mAP@0.5, and mAP@0.5:0.95**.
- Focused evaluation on **small-object detection** in constrained data environments.




---

## Key Findings

The benchmark demonstrates that **YOLOv8n** provides the strongest balance between feature generalization and inference efficiency on limited-data scenarios, achieving:

| Metric | Result |
|--------|--------|
| Precision | **97.44%** |
| Recall | **94.48%** |
| mAP@0.5 | **98.09%** |
| mAP@0.5:0.95 | **64.13%** |

These findings indicate that architectural complexity alone does not guarantee better performance; **dataset scale and annotation consistency significantly influence detector generalization**.

<p align="center">
  <img src="https://github.com/user-attachments/assets/fc95ed13-e860-4f0b-8db5-0449bc5011dc" width="850"/>
</p>

---

## Sample Prediction

<p align="center">
  <img src="https://github.com/user-attachments/assets/46d9d2a8-7a00-4c64-878b-5f423c7e05d0" width="450"/>
</p>



---

## Tech Stack

`Python` • `PyTorch` • `Torchvision` • `OpenCV` • `CUDA` • `Roboflow` • `COCO` • `YOLO Annotation Format`

---

## Publication

**A Comparative Analysis of YOLOv12, YOLOv8, Faster R-CNN, and SSD300 for Landmine Detection**

*IEEE International Conference on Emerging Computing and Intelligent Technologies (ICoECIT 2026).*
