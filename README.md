# YOLOv8 + SAM 2 — Detection & Segmentation Pipeline
A complete pipeline for object detection (YOLOv8) and segmentation (SAM 2) with training in Google Colab and local use.

## Features
- Training YOLOv8 on dataset in Google Colab
- Zero-shot segmentation via SAM 2 without additional training
- Automatic saving of weights to Google Drive
- Ready-made inference script for local launch
- Support for your own datasets and Roboflow

## Training Results (COCO128)
| Metric | Result |
|---|---|
| mAP50 | 0.943 |
| mAP50-95 | 0.837 |
| Inference (CPU) | ~265ms / photo |

## Notebook Structure
| Cell | Description |
|---|---|
| 1 | Installing Dependencies |
| 2 | Connecting Google Drive |
| 3 | Preparing the Dataset |
| 4 | Creating data.yaml |
| 5 | Training YOLOv8 |
| 6 | Training Graphs |
| 7 | Loading SAM 2 |
| 8 | Pipeline YOLOv8 + SAM 2 |
| 9 | Single-Photo Test |
| 10 | Saving Weights |
