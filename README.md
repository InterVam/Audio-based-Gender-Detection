# Voice Gender Detection Model

## Overview
This project presents a cutting-edge Voice Gender Detection model, meticulously developed using PyTorch. It's designed to accurately classify voice recordings into male or female categories. The core of this project lies in its robust utilization of audio processing techniques and advanced neural network architectures to achieve high accuracy levels.

## Key Features

- **High Accuracy Classification**: Harnesses the power of PyTorch to build a model capable of distinguishing between male and female voices with remarkable precision.

- **Advanced Audio Processing**: Employs the `torchaudio` library for sophisticated audio signal processing, leveraging Mel Spectrograms to extract the essential features of audio signals effectively.

- **Custom CNN Architecture**: Features a tailor-made Convolutional Neural Network (CNN) with multiple convolutional layers, batch normalization, dropout layers for regularization, and max-pooling layers. This architecture is finely tuned to capture the spectral features of audio data.

- **Efficient Data Handling**: Introduces a custom `AudioDataset` class, designed to streamline the handling, loading, preprocessing, and augmentation of audio data. This ensures seamless integration with PyTorch's DataLoader for efficient batch processing.

- **Balanced Dataset Utilization**: Prioritizes fairness and bias prevention by employing a meticulously balanced dataset, representing male and female voices equally.

- **Hyperparameter Optimization**: Engages in rigorous fine-tuning of hyperparameters, including the learning rate, batch size, and epochs, to enhance model performance optimally.

- **Comprehensive Performance Evaluation**: Utilizes a suite of metrics such as accuracy, precision, recall, F1-score, and confusion matrices for a thorough analysis and evaluation of model performance.

- **Insightful Visualizations**: Incorporates visualizations of Mel Spectrograms, providing deep insights into the model's feature extraction focus and ensuring the significance of the processed audio signals.

- **Data Version Control**: Implements DVC (Data Version Control) to ensure efficient data management and reproducibility of experiments, maintaining the integrity of the project's development process.

- **Collaboration and Version Control**: Leverages Git for robust version control, facilitating seamless collaboration and efficient project management.

- **Optimized Performance on CUDA**: Optimizes computing performance for model training and inference by deploying the model on CUDA-enabled devices, significantly reducing computation times.

## Getting Started

To explore this Voice Gender Detection model, clone this repository and follow the setup instructions detailed below. Ensure you have a CUDA-enabled device for optimal performance. 

```bash
git clone <repository-url>
cd voice_gender_detection
