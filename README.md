# Road Damage Segmentation

## Introduction

This project focuses on detecting and segmenting road damages such as cracks and potholes from road video frames using image processing techniques. Image segmentation is used to separate damaged road areas from normal road surfaces for easier analysis.

The system first enhances video frames to reduce noise and improve visibility. Then, segmentation techniques are applied to identify damaged regions more accurately. The detected damage areas are highlighted and evaluated using performance metrics such as Accuracy, Precision, Recall, F1 Score, and IoU.

The main goal of this project is to support automatic road damage detection and improve road inspection efficiency.

---


# Technologies Used

- Python
- OpenCV
- NumPy

---

# Processing Pipeline
- Enhancement
- Gaussian Blur
- Otsu Threshold
- ROI (Region of Interest)
- Morphology
- Contours
- Filtering
- Output


## Image Segmentation
Road damage areas are segmented using:
- Otsu Thresholding
- Region of Interest (ROI)
- Morphological operations
- Contour detection

## Evaluation
The segmentation results are evaluated using:
- Accuracy
- Precision
- Recall
- F1 Score
- IoU
- Dice Coefficient

---

# Project Structure

```text
road-damage-detection/
│
├── frame/                 # Original extracted frames
├── enhanced/              # Enhanced frames
├── threshold/             # Threshold output images
├── morphology/            # Morphology processed images
├── masks/                 # Segmentation masks
├── output/                # Final detected outputs
├── ground_truth/          # Ground truth masks for evaluation
├── final_video.mp4        # Input road video
├── final_segmentation.py                # Main project source code
└── README.md              # Project documentation
```

---



Press `ESC` to stop the video processing window.

---

# Evaluation Frames

The following frames are used for evaluation:

```python
test_frames = [109, 164, 223, 366, 416, 421]
```

---

# Output

The system generates:
- Enhanced images
- Threshold images
- Morphology outputs
- Segmentation masks
- Final detected road damage outputs

---


# Author

Road Damage Detection 

Group 12
