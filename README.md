# Underwater Image Classification

This repository contains the implementation and findings of our **Final Year Project** on underwater image classification, a study conducted to address the unique challenges of underwater environments using advanced deep learning techniques.

## Project Overview

Underwater image classification plays a critical role in marine biodiversity conservation, underwater archaeology, and aquatic pollution monitoring. This project focuses on overcoming challenges such as poor visibility, varying light conditions, and domain shifts caused by different water types. It compares models like Faster R-CNN and Boosting R-CNN to analyze their performance in underwater settings.

### Features:
- **Dataset**: Utilized the **TrashCan dataset**, comprising over 7500 annotated images.
- **Models**: Compared two state-of-the-art object detection models:
  - **Faster R-CNN**: Known for its robust two-stage detection and precise instance segmentation.
  - **Boosting R-CNN**: Integrates RetinaRPN, boosting mechanisms, and probabilistic inference for challenging underwater conditions.
- **Metrics**: Evaluated models using metrics like AP (Average Precision), IoU (Intersection over Union), and qualitative analysis.

---

## Key Sections in the Repository

1. **Report**: Includes the full project documentation, detailing methodology, results, and comparative analysis.
2. **Source Code**: Implementation scripts for preprocessing, training, and evaluating the Faster R-CNN and Boosting R-CNN models.
3. **Dataset Preparation**: Scripts for preparing and augmenting the TrashCan dataset.
4. **Results**: Graphs, tables, and qualitative results demonstrating model performance.
5. **Future Scope**: Recommendations for improving underwater image classification systems.

---

## Technologies Used

- **Programming Languages**: Python
- **Libraries**: TensorFlow, PyTorch, OpenCV, MMDetection
- **Models**: Faster R-CNN, Boosting R-CNN
- **Tools**: Jupyter Notebook, Visual Studio Code

---

## Results

- **Faster R-CNN**: Achieved high precision in object detection but struggled with overlapping objects.
- **Boosting R-CNN**: Demonstrated superior performance in challenging conditions, addressing issues like occlusion and low contrast.

---

## Future Scope

- Expand dataset diversity for broader aquatic conditions.
- Develop lightweight models for deployment on mid-range devices.
- Integrate models with Autonomous Underwater Vehicles (AUVs) and Remote Operated Vehicles (ROVs).

---

## Contributors

- **Tanmoy Sarkar**
- **Amelia Debbarma**
- **Parthiv Nath**
- **Anamika Debnath**

Supervised by **Dr. Ranjita Das**, Assistant Professor, NIT Agartala.
