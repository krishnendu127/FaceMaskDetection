Face Mask Detection Project

This project is focused on building a convolutional neural network (CNN) to detect whether a person is wearing a face mask or not in an image. The dataset used for this project contains images of people with and without masks.

Dataset

The dataset used in this project is available on Kaggle: Face Mask Dataset.

It consists of two categories of images:

Images with people wearing face masks.
Images with people not wearing face masks.

Approach

The project follows these main steps:

Data Preparation: Images are resized, converted to numpy arrays, and split into training and testing sets.
Model Building: A convolutional neural network (CNN) is constructed using TensorFlow and Keras. The model architecture includes convolutional layers, max-pooling layers, dropout layers, and fully connected layers.
Training: The CNN model is trained on the training data with the Adam optimizer and sparse categorical cross-entropy loss function.
Evaluation: The model's performance is evaluated on the test data to measure its accuracy in detecting face masks.
Prediction: The trained model is used to predict whether a person is wearing a face mask or not in new images.

Results

The CNN model achieved a test accuracy of 91% on the test dataset, indicating its effectiveness in face mask detection.

How to Use

Clone the repository to your local machine.
Install the required dependencies using pip install -r requirements.txt.
Run the FaceMaskDetection.ipynb notebook to train the model and evaluate its performance.
Use the trained model to make predictions on new images by providing the image path.
