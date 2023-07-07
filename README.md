<h1><center><img src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/e9047d29-4775-47c9-b180-1d0069f14544/d5ecndw-981695a8-2828-479a-b2ad-3c21896b255c.gif?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7InBhdGgiOiJcL2ZcL2U5MDQ3ZDI5LTQ3NzUtNDdjOS1iMTgwLTFkMDA2OWYxNDU0NFwvZDVlY25kdy05ODE2OTVhOC0yODI4LTQ3OWEtYjJhZC0zYzIxODk2YjI1NWMuZ2lmIn1dXSwiYXVkIjpbInVybjpzZXJ2aWNlOmZpbGUuZG93bmxvYWQiXX0.62M-k34_mA_iHEAt8ontYRsknAZZCPO5xkxJc6PExsU"></center></h1>

# Cats vs Dogs Classification using Image Augmentation and Keras

This project demonstrates the classification of images into two categories: cats and dogs, using image augmentation techniques and the Keras library. The goal is to build a convolutional neural network (CNN) model that can accurately classify images of cats and dogs.

## Dataset

The dataset used for this project consists of a large number of labeled images of cats and dogs. The dataset is sourced from the Microsoft Cats vs Dogs dataset, which can be downloaded from [here](https://www.microsoft.com/en-us/download/confirmation.aspx?id=54765). After downloading and extracting the dataset, the images are organized into separate directories for cats and dogs.

## Image Augmentation and Data Preparation

Image augmentation techniques are applied to the training dataset using the Keras `ImageDataGenerator` class. This helps to artificially expand the training dataset and improve the model's ability to generalize to new images. The augmented images are then split into training and validation sets using a specified split size.

## Model Architecture

The model architecture used for this project is a CNN implemented in Keras. It consists of multiple convolutional layers with batch normalization, max pooling, and dropout layers to prevent overfitting. The model is compiled with the RMSprop optimizer and binary cross-entropy loss function.

## Training and Evaluation

The model is trained on the augmented training dataset using the `fit` method in Keras. The training process is run for a specified number of epochs, and the training and validation accuracy and loss are recorded. The model's performance is evaluated on the validation dataset to assess its accuracy and generalization capability.

## Results and Visualization

The training and validation accuracy and loss are plotted for each epoch to visualize the model's training progress. This helps to analyze the model's performance and identify overfitting or underfitting issues.

## Prediction

Once the model is trained and evaluated, it can be used to make predictions on new images of cats or dogs. The `predict.py` script is provided, which takes the path to an image as input and outputs the predicted class label.

## Conclusion

This project demonstrates the implementation of a cats vs dogs image classification model using image augmentation techniques and the Keras library. By leveraging image augmentation and a well-designed CNN architecture, the model achieves good accuracy in distinguishing between cats and dogs. Feel free to explore and modify the code to further enhance the model's performance or apply it to different image classification tasks.
