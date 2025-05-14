# Polyp Segmentation using DeepLabv3+ and DINOv2

This project compares two segmentation models — **DeepLabv3+ (CNN)** and **DINOv2 (Transformer)** — on the **Kvasir-SEG** dataset for binary polyp segmentation.

## Models

- **DeepLabv3+**: Traditional CNN architecture.
- **DINOv2**: Transformer-based model with a frozen backbone.

## Dataset

- **Kvasir-SEG**: 1000 annotated polyp images.
- Source: [Kvasir Dataset](https://datasets.simula.no/kvasir-seg/)

## Results

| Model       | Dice Score | IoU     |
|-------------|------------|---------|
| DeepLabv3+  | 0.8600     | 0.7512  |
| DINOv2      | 0.8671     | 0.7638  |


