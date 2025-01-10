# Chest X-Ray Classification for Cardiomegaly Detection

This project focuses on classifying chest X-ray images to detect the presence of cardiomegaly (an enlarged heart). Using deep learning techniques, specifically the DenseNet-121 architecture, this model aims to assist in accurate medical diagnostics.

## Dataset

- The dataset contains over **10,000+ chest X-ray images**.
- Images were preprocessed using **histogram equalization** to enhance contrast and reduce noise, resulting in clearer samples for the classifier.

- ![Chest X-Ray Example]([images/chest_xray_sample.png](https://raw.githubusercontent.com/Aman-Khokhar18/X_Ray_Classification/refs/heads/main/images/output.png))

## Model Architecture

- The model utilizes the **DenseNet-121** architecture, known for its efficient feature reuse and high performance on image classification tasks.

## Training Details

### Hyperparameters

- **Learning Rate**: 1e-5
- **Weight Decay (L2 Regularization)**: 1e-2
- **Batch Size**: Appropriate batch size used (adjust according to available resources)

### Optimizer and Regularization

- Applied **L2 regularization** to reduce overfitting.
- **Weight decay** value set to **1e-2**.

### Learning Rate Scheduler

- Implemented a **plateau learning rate scheduler** with:
  - **Patience**: 2 epochs
  - **Factor**: 0.1 (reduces learning rate by a factor of 0.1 when a plateau is detected)

### Early Stopping

- Used **early stopping** with a patience of 4 epochs to prevent overfitting.

## Results

- Include details about the model’s accuracy, F1-score, or other relevant metrics if available.

## Usage

1. Clone this repository.
2. Prepare the dataset as per the required structure.
3. Run the jupyter notebook provided.

## Future Improvements

- Experimenting with additional image preprocessing techniques.
- Testing alternative model architectures such as ResNet or EfficientNet.
- Fine-tuning hyperparameters for further performance gains.


Feel free to customize and add more sections like Installation, Contributing, or additional notes specific to your project.

