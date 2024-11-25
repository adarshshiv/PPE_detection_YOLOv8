# Construction Site Safety Detection Using YOLOv8

This project focuses on training a YOLOv8 model to detect Personal Protective Equipment (PPE) and other elements at construction sites, such as hard hats, safety vests, and machinery. The goal is to improve safety monitoring by identifying if workers are equipped with the necessary safety gear.

---

## Features

- **Object Detection:** Identifies objects such as hard hats, masks, safety vests, and other PPE.
- **Custom Dataset:** Trained on a robust dataset specifically for construction site safety monitoring.
- **YOLOv8 Model:** Utilizes the state-of-the-art YOLOv8 architecture for fast and accurate object detection.
- **Deployment-Ready:** Model is ready to be exported and used in real-world scenarios.

---

## Dataset

The dataset used is the **Construction Site Safety Image Dataset** from Roboflow, containing images for training, validation, and testing. The dataset includes labeled images of:

- Hardhat
- Mask
- No Hardhat
- No Mask
- No Safety Vest
- Person
- Safety Cone
- Safety Vest
- Machinery
- Vehicle

## Dataset Structure

The dataset is organized into `train`, `valid`, and `test` sets, each containing `images` and corresponding `labels`. This structure follows the YOLO format required for training.

