# IMAGE-CLASSIFICATION-MODEL

## COMPANY

CODTECH IT SOLUTIONS

## NAME

MUDRAGIRI DEEKSHITH NARAYAN

## INTERN ID

CITS17

## DOMAIN

MACHINE LEARNING

## DURATION

4 WEEKS

## MENTOR

NEELA SANTOSH

---

# DESCRIPTION OF TASK: CNN BASED IMAGE CLASSIFICATION MODEL

This project focuses on developing an Image Classification Model using Convolutional Neural Networks (CNN) and TensorFlow. Image classification is a fundamental task in Computer Vision where a machine learning model is trained to identify and categorize images based on their visual content. The primary objective of this project is to build a Deep Learning model capable of accurately recognizing handwritten digits using the MNIST dataset.

The MNIST dataset is one of the most popular benchmark datasets in Machine Learning and Computer Vision. It consists of 70,000 grayscale images of handwritten digits ranging from 0 to 9. Each image has a resolution of 28 × 28 pixels. The dataset is divided into 60,000 training images and 10,000 testing images. Since the dataset is readily available within TensorFlow, it can be loaded directly without requiring manual downloads.

The project was implemented using Python along with TensorFlow, Keras, NumPy, and Matplotlib libraries. TensorFlow and Keras were used to design, train, and evaluate the Convolutional Neural Network, while Matplotlib was used for visualization of images and prediction results.

Initially, the MNIST dataset was loaded and preprocessed. The pixel values of all images were normalized by dividing them by 255, transforming the values into the range of 0 to 1. This normalization process improves the learning efficiency and stability of the neural network during training.

Since CNN models require image data in a channel format, the images were reshaped into dimensions of 28 × 28 × 1, where the final dimension represents the grayscale color channel.

The Convolutional Neural Network architecture was then developed using multiple layers. Convolutional (Conv2D) layers were employed to automatically extract important image features such as edges, curves, textures, and shapes. MaxPooling layers were incorporated to reduce the spatial dimensions of feature maps while retaining important information, thereby improving computational efficiency.

After feature extraction, a Flatten layer was used to convert the multidimensional feature maps into a one-dimensional vector suitable for classification. Dense (Fully Connected) layers were then added to perform the final classification task. The output layer utilized the Softmax activation function to classify each image into one of the ten digit categories from 0 to 9.

The model was compiled using the Adam optimizer and Sparse Categorical Crossentropy loss function. Accuracy was selected as the evaluation metric. During training, the CNN model learned patterns from thousands of handwritten digit images over multiple epochs and continuously improved its prediction capability.

Once training was completed, the model was evaluated on the testing dataset. The CNN achieved an accuracy of approximately 99%, demonstrating excellent performance in handwritten digit recognition. The trained model was further tested on sample images from the test dataset, successfully predicting the correct digit labels.

For example, when an image containing the handwritten digit “7” was presented to the model, it correctly identified and predicted the output as “7”. This confirms that the CNN effectively learned meaningful image features and classification patterns from the training data.

This project provides practical exposure to Deep Learning concepts such as image preprocessing, feature extraction, convolutional operations, neural network training, prediction, and model evaluation. It also demonstrates the effectiveness of Convolutional Neural Networks in solving image recognition problems.

Overall, the project successfully implemented a CNN-based Image Classification System using TensorFlow and achieved high classification accuracy on the MNIST dataset. The knowledge gained from this project can be applied to advanced Computer Vision applications such as facial recognition, medical image analysis, handwritten text recognition, autonomous systems, and object detection.

---

# TECHNOLOGIES USED

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib

---

# FEATURES

* Image Preprocessing and Normalization
* CNN-based Feature Extraction
* Handwritten Digit Classification
* Model Training and Testing
* Accuracy Evaluation
* Sample Image Prediction
* Visualization of Results

---

# DATASET USED

**MNIST Handwritten Digits Dataset**

* Total Images: 70,000
* Training Images: 60,000
* Testing Images: 10,000
* Image Size: 28 × 28 Pixels
* Classes: Digits 0 to 9

---

# OUTPUT

* Trained CNN Model
* Test Accuracy (~99%)
* Sample Image Predictions
* Accuracy and Loss Graphs
* Classification Results

---

# RESULT

The Convolutional Neural Network successfully classified handwritten digit images with high accuracy. The model demonstrated excellent performance on unseen test data and effectively recognized digit patterns from the MNIST dataset.

---

# CONCLUSION

The CNN-based Image Classification Model was successfully developed using TensorFlow and Keras. The model achieved outstanding performance on the MNIST dataset and demonstrated the effectiveness of Deep Learning techniques in image recognition tasks. This project provides a strong foundation for exploring advanced Computer Vision and Artificial Intelligence applications.
