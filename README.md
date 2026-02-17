# Grad-CAM: Where is your CNN Looking?
An implementation of **Gradient-weighted Class Activation Mapping (Grad-CAM)** to interpret and visualize the decision-making process of Convolutional Neural Networks.

## 🚀 Overview
This repository provides tools to "see" through the eyes of a model. By producing heatmaps, we can verify if a network is focusing on relevant features or simply picking up on background noise.

## ✨ Key Experiments
- **General Visualizations:** Interpreting standard ImageNet-style classifications.
- **Feature Highlighting:** Specific implementation to 'find' and highlight **sunglasses** within an image using class activation maps.

## 🛠 Features
- Uses **Guided Backpropagation** for high-resolution class-discriminative visualizations.
- Compatible with modern PyTorch architectures.

## 📂 Repository Structure
- `Grad-Cam1.ipynb`: Core implementation and general visualizations.
- `Grad-cam2.ipynb`: Specialized visualization for feature detection (e.g., sunglasses).