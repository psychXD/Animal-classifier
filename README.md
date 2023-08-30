Animal Classifier Project

In this project, I've developed a Convolutional Neural Network (CNN) model to classify images of various animals into different classes. The classes I focused on are 'bear', 'ostrich', 'pigs', 'horses', 'owl', and 'gorilla'.
Objective

The primary objective of this project was to build a classifier that could accurately distinguish between different animal classes based on their images. By training a CNN model on a diverse dataset containing images of the selected animal classes, I aimed to achieve a high level of accuracy in classification.
Dataset

For this project, I collected images from various sources to create a diverse and representative dataset. Here are the links to the datasets I used for each animal class:

    Horse Dataset
    Pig Dataset
    Owl Dataset
    Gorilla Dataset
    Bear Dataset
    Ostrich Dataset
    Buffalo Dataset

Model Architecture

I designed a CNN model architecture tailored for image classification tasks. The model architecture includes multiple convolutional layers to extract relevant features from the images, followed by max-pooling layers for downsampling. The extracted features are then flattened and passed through fully connected layers to make class predictions. The model is trained using the categorical cross-entropy loss and optimized using the Adam optimizer.
Results

After extensive training and validation, I achieved an impressive final accuracy of 93 percent on the test dataset. This accuracy reflects the model's ability to correctly classify animals from the specified classes.
Real-time Animal Detection

Additionally, I integrated the OpenCV (cv2) library to extend the project's functionality. Using the trained model, I implemented real-time animal detection through the camera. By processing live camera feed, the model can identify and label animals from the specified classes in real-time.
