# Image-Classification-using-CNN-Cats-Dogs
CNN-based image classification model that distinguishes between cats and dogs using deep learning with TensorFlow/Keras.

The notebook implements a Convolutional Neural Network (CNN) for binary image classification of cats and dogs using TensorFlow/Keras.

# 1. Data Preprocessing

Images are resized to a fixed input shape suitable for CNNs.

Pixel values are normalized to improve training stability.

ImageDataGenerator is used for real-time data augmentation (rotation, flipping, zooming, shifting) to reduce overfitting.

# 2. Model Architecture

Multiple Conv2D layers with ReLU activation and MaxPooling2D for feature extraction.

Flatten layer to convert feature maps into a 1D vector.

Fully connected Dense layers with dropout to reduce overfitting.

Final output layer with a sigmoid activation function for binary classification.

# 3. Training

Loss Function: Binary Crossentropy

Optimizer: Adam

Evaluation Metric: Accuracy

Early stopping or model checkpointing can be used to prevent overfitting.

# 4. Evaluation & Visualization

Model performance is tracked on training and validation sets.

Accuracy and loss curves are plotted after training.

Final evaluation on unseen test data provides classification performance.
