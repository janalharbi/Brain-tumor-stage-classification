# Brain Tumor Stage Classification Using MRI Scans 🧠

## About the Project

This project aims to develop a deep learning-based system for classifying brain tumor stages using Magnetic Resonance Imaging (MRI) scans.

Unlike systems that focus only on detecting the presence of a tumor, this project focuses on classifying glioma tumor grades to support tumor progression monitoring and treatment planning.

## Objectives

- Classify glioma tumors into WHO Grade II, III, and IV.
- Develop a deep learning model for MRI-based tumor classification.
- Support tumor progression monitoring.
- Assist healthcare professionals in treatment planning.
- Improve the interpretability of AI predictions using Explainable AI.

## Dataset

The project uses the UCSF Preoperative Diffuse Glioma MRI (UCSF-PDGM) Dataset.

The dataset contains MRI scans of adult patients with diffuse gliomas and includes multiple MRI sequences such as T1, T1 post-contrast, T2, FLAIR, DWI, and SWI.

## Deep Learning Models

The project investigates several deep learning architectures:

- CNN
- ResNet
- MobileNetV2

ResNet50 with Grad-CAM is also used to visualize the MRI regions that contribute to the model's predictions.

## System Workflow

MRI Images → Preprocessing → Tumor Analysis → Deep Learning Model → Tumor Grade Classification → Prediction & Visualization

## Technologies

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- OpenCV
- Matplotlib
- CNN
- ResNet
- MobileNetV2
- Grad-CAM

## Evaluation

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score

## Future Work

- Improve model generalization.
- Optimize lightweight models.
- Enhance Explainable AI techniques.
- Improve clinical integration.
- Test the system on additional unseen MRI data.

## Disclaimer

This project is developed for academic and research purposes and is not intended to replace professional medical diagnosis or clinical judgment.
