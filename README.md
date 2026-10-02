# Medical Waste Classification Using Deep Learning

## Project Overview

This project explores the use of Computer Vision and Deep Learning
to automatically classify medical waste.

The objective is to investigate whether image classification can
support automated medical waste sorting and reduce dependence on
manual classification.

## Problem

Manual medical waste sorting can expose workers to contaminated
materials and accidental injuries.

This project explores an automated classification pipeline:

Camera → Image Preprocessing → CNN → Waste Classification → Sorting

## Dataset

The dataset contains approximately 4,000 medical waste images
across four categories:

- Mask
- Gloves
- Syringe
- Medicine

## Methodology

The project includes:

1. Image preprocessing
2. Image normalization
3. Data augmentation
4. CNN model training
5. Model comparison
6. Model evaluation

### Models Compared

- ResNet50
- EfficientNet-B0
- MobileNetV2

## Results

ResNet50 achieved the highest reported classification accuracy:

**Accuracy: 94%**

## Proposed System

The proposed workflow is:

Camera
↓
Image Preprocessing
↓
CNN Classification
↓
Classification Result
↓
Automated Sorting

## Business / Operational Implications

The proposed system could potentially:

- Reduce dependence on manual classification
- Support safer medical waste handling
- Enable automated sorting workflows
- Provide a foundation for real-time waste classification

However, the current result is based on model evaluation.
Real-world deployment would require further testing under different
lighting conditions, object orientations, occlusion, camera positions,
and conveyor-belt environments.

## Future Work

- Real-time object detection
- Edge-device deployment
- Real-world dataset collection
- Conveyor-belt testing
- Threshold and confidence analysis
- Integration with automated sorting hardware

## Portfolio

A presentation describing the project is available in:

`reports/Medical_Waste_AI_Portfolio.pdf`
