# Facial Recognition System with Sequential Neural Network and Autoencoder

## Overview

This GitHub repository contains the code and documentation for a facial recognition system based on a Sequential Neural Network with an autoencoder layer. The model has been trained on batch images of our classmates, each labeled with a respective identifier. The dataset is saved and split using `np.savez('insofe2020_dataset.npz', images=images, labels=labels)`.

## Key Features

* Employs an autoencoder layer for efficient feature extraction and dimensionality reduction.
* Utilizes a sequential neural network architecture for classification.
* Handles image loading, preprocessing, and dataset splitting.
* Provides insights on potential improvements for real-world performance.

## Limitations and Potential Improvements

While the current model performs well on the provided dataset, it is important to acknowledge its limitations and consider potential improvements for real-world applications.

* **Dataset Limitations:** The dataset contains burst images with only 2-3 variations per person. If applied to real-world data, the model may not perform as well.

* **Data Augmentation:** Techniques like data augmentation can be employed to increase the size of the training set. Capturing more diverse images, including different angles, is recommended to improve the model's performance.

* **Preprocessing with Face Detection:** Integrating a face detection model as a preprocessing step can enhance the system's performance on real-world data. Using the output of the face detection model to build other models can lead to more accurate predictions.

Consider these suggestions to enhance the system's robustness and adaptability in a broader range of scenarios. Regular updates and improvements to the dataset and model architecture will contribute to the effectiveness of the facial recognition system.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use and modify the code as needed. Contributions are welcome!
