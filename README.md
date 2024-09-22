# Leukemia Detection using Deep Learning and Computer Vision

This project applies **deep learning** and **computer vision** techniques to classify and detect **acute lymphoblastic leukemia (ALL)** from blood smear images. We leverage **CNNs** such as EfficientNet B3, VGG16, and ResNet50 to build an automated, accurate system for classifying benign and malignant cells.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Models and Techniques](#models-and-techniques)
- [Results and Analysis](#results-and-analysis)
- [How to Run](#how-to-run)
- [License](#license)

## Overview
Leukemia, particularly **Acute Lymphoblastic Leukemia (ALL)**, is a type of blood cancer that affects white blood cells. Early detection is key for effective treatment. This project uses **Convolutional Neural Networks (CNNs)** to analyze blood smear images and differentiate between **benign** and **malignant** cells, with a focus on classifying **ALL subtypes**.

## Dataset
- **Total Images**: 3242 PBS images
- **Patients**: 89
- **Classes**: Benign (Hematogones), Malignant (Early Pre-B, Pre-B, Pro-B ALL)
- **Preprocessing**: Image resizing (224x224), segmentation, data augmentation (flipping, scaling)

## Models and Techniques

### **EfficientNet B3**
- **Training Accuracy**: 95.56%
- **Validation Accuracy**: 93.75%

### **ResNet50**
- **Best Accuracy**: 91.32%
- Uses **residual learning** to solve the vanishing gradient problem.

### **Custom CNN**
- **Accuracy**: 97.7%
- Best for **leukemia stage classification**, optimized with 6 convolutional layers.

## Results and Analysis
- **Custom CNN** achieved the highest accuracy for **leukemia stage classification** at **97.7%**.
- Models show strong generalization and performance across diverse datasets.

## How to Run

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/leukemia-detection.git
    cd leukemia-detection
    ```

2. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Train the model**:
    ```bash
    python train.py --model EfficientNetB3
    ```

4. **Evaluate the model**:
    ```bash
    python evaluate.py --model EfficientNetB3
    ```

## License
This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for more details.
