# Automated Quality Inspection System for Manufacturing

This project implements an automated visual quality inspection system for manufacturing using computer vision techniques.

## Problem Statement
Manufacturing facilities require automated inspection systems to detect defects in products before packaging. Manual inspection is time-consuming and error-prone. This project demonstrates a prototype solution for detecting and classifying defects on manufactured items.

## Manufactured Item
Printed Circuit Board (PCB)

## Defect Types Detected
- Scratch
- Misalignment
- Missing Component

## Methodology
- A sample PCB image is analyzed using OpenCV
- Edge detection and contour analysis are used to localize defect regions
- Rule-based logic is applied to classify defect types
- Confidence scores are assigned to each detected defect
- Defect center pixel coordinates (x, y) are computed
- Severity is assessed based on defect area (Low / Medium / High)

## Output
For each detected defect, the system provides:
- Defect type
- Confidence score
- (x, y) pixel center coordinates
- Severity assessment
- Bounding box visualization on the image

## Project Structure
automated-quality-inspection/
├── Task2_Quality_Inspection.ipynb
├── images/
│ └── pcb_test.jpg
├── output/
│ └── inspection_result_final.jpg
├── README.md

## Tools & Technologies
- Python
- OpenCV
- NumPy
- Matplotlib
- Google Colab

## Conclusion
This project demonstrates a complete automated quality inspection pipeline suitable for early-stage manufacturing defect detection. The system is lightweight, explainable, and effective for prototype-level industrial applications.
