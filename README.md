# 3D-Object-Classification
3D object classification using the ModelNet40 dataset
# Project_Update

This project is a Jupyter Notebook where I worked on building and training a point cloud classification model using deep learning techniques. The notebook walks through the entire pipeline — from data loading and preprocessing to training and evaluating the model.

## 🔍 What’s Inside

- **Dataset Handling**: Code to load, normalize, and prepare 3D point cloud datasets for training and testing.
- **Data Augmentation**: Includes jittering, random rotations, and scaling to make the model robust.
- **Model Architecture**: A neural network model inspired by PointNet, which includes input and feature transformation networks, followed by global feature extraction and fully connected layers.
- **Training Process**: The model is compiled and trained using Keras, with accuracy and loss tracked across epochs.
- **Saving & Visualization**: The trained model is saved, and training history is visualized with accuracy/loss plots. There’s also a section for visualizing predictions on test data.

This project helped me understand the flow of working with 3D data, applying augmentation techniques, and building a deep learning pipeline specifically for point cloud classification tasks.

> Just a personal learning project — not meant for production use.
