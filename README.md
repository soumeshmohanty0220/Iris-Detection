# Iris Tracking Model with Keypoint Detection

## Project Name - GazeNet
## Project Summary

This project implements an advanced iris tracking model using keypoint detection techniques with TensorFlow and Python. The primary objective is to accurately detect and track the keypoints of the iris in both static images and live video streams. The model leverages the powerful ResNet152V2 architecture, fine-tuned for our specific task, providing robust performance in various lighting conditions and environments.

### Key Features:
- **Data Loading and Preprocessing:** Efficient handling and preprocessing of training, validation, and test datasets.
- **Model Architecture:** Utilizes ResNet152V2 for feature extraction, followed by custom layers for keypoint prediction.
- **Training:** Optimized training with the Adam optimizer and Mean Squared Error loss, incorporating data augmentation techniques.
- **Evaluation:** Comprehensive evaluation on a test set, with visualization of predicted keypoints.
- **Live Demo:** Real-time iris tracking using a webcam, demonstrating the model's practical application.

### Applications:
- **Security Systems:** Enhanced biometric authentication methods.
- **Medical Diagnostics:** Non-invasive eye movement tracking for diagnostic purposes.
- **Human-Computer Interaction:** Advanced gaze tracking for user interface control and accessibility.
