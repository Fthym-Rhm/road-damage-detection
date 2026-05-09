# Road Damage Enhancement

## Introduction

This project focuses on enhancing road damage video frames using image processing techniques in Python with OpenCV.  
The enhancement pipeline improves the visibility and quality of road surface details, making it easier for further analysis and detection of road damages such as cracks and potholes.

The system processes video frames step-by-step and saves the output of each enhancement stage separately for analysis and comparison.

---

## Technologies Used

- Python
- OpenCV
- NumPy
- Matplotlib
---

## Enhancement Pipeline

- Grayscale
- Median Filter
- Log Transform
- Contrast Stretch
- Histogram Equalization

## Folder Structure

The program automatically creates folders to save outputs from each stage.

```text
gray/        -> Grayscale images
median/      -> Median filtered images
log/         -> Log transformed images
contrast/    -> Contrast stretched images
enhanced/    -> Final enhanced images
```



### Run the Program

```bash
final_enhancement.py
```

##  Project Branch Navigation

-  Main branch (overview & stable code):  
  https://github.com/Fthym-Rhm/road-damage-detection/tree/main

-  Enhancement branch (Enhancement pipeline implementation):  
  https://github.com/Fthym-Rhm/road-damage-detection/tree/enhancement

- Segmentation branch
   https://github.com/Fthym-Rhm/road-damage-detection/tree/segementation

## Author 
Road Damage Enhancement System

Group 12
