# Audio-based-Gender-Detection
Developed a Voice Gender Detection model using PyTorch, capable of classifying voices as male or female with high accuracy.
Utilized the torchaudio library for audio processing and feature extraction, specifically employing Mel Spectrograms to capture the essence of audio signals.
Implemented a custom Convolutional Neural Network (CNN) architecture comprising multiple convolutional layers, batch normalization, dropout for regularization, and max-pooling layers to effectively learn from the spectral features of the audio data.
Crafted a custom AudioDataset class to efficiently handle audio data loading, preprocessing, and augmentation, ensuring compatibility with PyTorch's DataLoader for batch processing.
Conducted experiments with a balanced dataset, ensuring equal representation of male and female voices, to prevent model bias.
Fine-tuned hyperparameters, including learning rate, batch size, and the number of epochs, to optimize model performance.
Evaluated model performance using metrics such as accuracy, precision, recall, F1-score, and confusion matrices, ensuring comprehensive analysis.
Visualized Mel Spectrograms to understand the model's focus and ensure meaningful feature extraction from audio signals.
Incorporated DVC (Data Version Control) for efficient data management and to ensure reproducibility of experiments.
Utilized Git for version control, facilitating collaboration and project management.
Deployed the model on a CUDA-enabled device, optimizing for performance and enabling faster inference times.
