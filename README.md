# Brain-Tumor-CLassification

This project implements a deep learning model for brain tumor classification using the MobileViT architecture. The model is trained on MRI images to classify tumors into glioma, meningioma, pituitary, and no tumor categories. It leverages CNN and Transformer-based features for efficient and accurate classification.

Features:
1.MobileViT-based model combining CNN and self-attention mechanisms.
2.Data augmentation for improved generalization.
3.Trained on Kaggle's Brain Tumor MRI Dataset with image size 256x256.
4.Early stopping & learning rate scheduling for optimized training.
Training Results:
1.Achieved 96%+ validation accuracy.
2.Trained using Adam optimizer with sparse categorical cross-entropy loss.
Usage:
1.Load the dataset and preprocess images.
2.Train the model using model.fit().
3.Evaluate and visualize results.
