# AudioClassification_UrbanSound8k
# Urban Sound Classification

## Description
This project aims to classify urban sounds using deep learning techniques. It utilizes the UrbanSound8K dataset, which contains various audio samples categorized into different classes such as air conditioner, car horn, dog bark, and more. The project implements both Artificial Neural Networks (ANN) and Convolutional Neural Networks (CNN) to achieve high accuracy in sound classification.

## Table of Contents
- [Data](#data)
- [Model Architecture](#model-architecture)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)


Data
The project uses the UrbanSound8K dataset, which can be downloaded from UrbanSound8K. Place the dataset in the data/UrbanSound8K/ directory.

The dataset contains audio files categorized into the following classes:

##
- Air Conditioner
- Car Horn
- Children Playing
- Dog Bark
- Drilling
- Engine Idling
- Gun Shot
- Jackhammer
- Siren
- Street Music

Model Architecture
Artificial Neural Network (ANN)

The ANN model consists of:
##
- Input layer with 1000 neurons
- Multiple hidden layers with Batch Normalization and Dropout to prevent overfitting
- Output layer with softmax activation for multi-class classification

Convolutional Neural Network (CNN)
The CNN model consists of:
##
- Two convolutional layers with max pooling
- Dropout layer to reduce overfitting
- Flattening layer followed by dense layers
- Output layer with softmax activation

Results
The models are evaluated based on accuracy, training time, and prediction time. The results are logged and can be visualized using bar plots for better understanding.

Example of Model Accuracy
<img width="1429" alt="Screenshot 2025-04-03 at 4 14 48 PM" src="https://github.com/user-attachments/assets/9994897b-b04f-48a7-b629-d74d6e86f14a" />


Example of Model Training Time
<img width="1416" alt="Screenshot 2025-04-03 at 4 15 11 PM" src="https://github.com/user-attachments/assets/677f37d2-e2b7-4846-b2c2-39eb314072c2" />


Example of Model Prediction Time
<img width="1426" alt="Screenshot 2025-04-03 at 4 15 23 PM" src="https://github.com/user-attachments/assets/102b6fe8-d171-4ded-a6f1-1cfc043097d1" />


Contributing:
##
- Contributions are welcome! If you have suggestions for improvements or want to add features, please fork the repository and submit a pull request. You can also open an issue to discuss potential changes.

License
##
- This project is licensed under the MIT License.

Acknowledgments:
##
- UrbanSound8K Dataset for providing the audio dataset.
- Librosa for audio analysis.
- TensorFlow and Keras for building and training deep learning models.
