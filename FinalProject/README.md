# 🌿 Plant Disease Detection Using Computer Vision

**ITAI 1378 – Final Project**  
**Student:** Denae Liong

---

## Project Overview

This project explores the use of computer vision and deep learning to identify plant diseases from images of plant leaves. The goal is to help farmers and growers detect diseases early so they can reduce crop loss and make better treatment decisions.

The proposed system uses a pretrained YOLO (You Only Look Once) model to analyze leaf images and predict the presence of plant diseases. The long-term goal is to provide users with a disease diagnosis along with suggested Integrated Pest Management (IPM) recommendations.

---

## Problem Statement

Plant diseases are a major cause of crop loss around the world. Traditional methods of identifying diseases often require expert knowledge and can be time-consuming. An AI-powered computer vision system can provide a faster and more accessible method for detecting diseases from leaf images.

---

## Dataset

**PlantVillage Dataset**

- 54,305 labeled images
- 38 plant disease and healthy classes
- Images of multiple plant species
- Publicly available dataset

Dataset:
https://www.kaggle.com/datasets/emmarex/plantdisease

---

## Technologies Used

- Python
- Ultralytics YOLO
- PyTorch
- OpenCV
- Jupyter Notebook

---

## Project Workflow

```
Leaf Image
      ↓
Image Preprocessing
      ↓
YOLO Model
      ↓
Disease Prediction
      ↓
Suggested IPM Guidance
```

---

## Current Status

This project was completed as a **proof of concept** for ITAI 1378.

The project includes:
- Research and project planning
- Computer vision workflow design
- Dataset selection
- Presentation and documentation

Due to time constraints, formal model training, testing, and performance evaluation were not completed before the final submission. Future work would include measuring accuracy, precision, recall, and inference speed using unseen test images.

---

## Future Improvements

- Train a custom YOLO model
- Evaluate model performance using a test dataset
- Improve disease classification accuracy
- Develop a mobile application for real-time plant disease detection
- Expand support for additional plant species

---

## Repository Structure

```
Plant-Disease-Detection/
│
├── notebooks/
├── src/
├── docs/
├── results/
├── README.md
└── requirements.txt
```

---

## Presentation

The final presentation for this project is included in the `docs` folder.

---

## Acknowledgments

- PlantVillage Dataset
- Ultralytics YOLO
- PyTorch
- OpenCV
- ITAI 1378 Computer Vision & AI
