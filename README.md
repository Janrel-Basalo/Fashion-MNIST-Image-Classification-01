# Fashion-MNIST-Image-Classification-01
 Google Colab Link : https://colab.research.google.com/drive/1O9ioiM8ls_mRp3eKjYQQK0E9jO_qQBjJ#scrollTo=xM2joG-yy-W3
## 1. What is the Fashion MNIST dataset?
     ### Ans. It's freely available and commonly used for learning computer vision.

## 2. Why do we normalize image pixel values before training?
     ### Ans. To make the output more faster, stable, and more reliable training.

## 3. List the layers used in the neural network and their functions.
     ### Ans. Flatten(input_shape=(28, 28)) - Converts the 28x28 pixel images into a 1D vector of 784 values (28 × 28 = 784)
              Dense(128, activation='relu') - Fully connected layer with 128 neurons
              Dense(10) - Output layer with 10 neurons (one for each clothing category)


## 4. What does an epoch mean in model training?
     ### Ans. A complete loop through all of your training data is called an epoch. Every sample is examined once by your model, which then learns from it and repeats the process. More laps               improve learning, but if your model completes too many, they will just memorize information rather than comprehend it.

## 5. Compare the predicted label and actual label for the first test image.
     ### Ans. The Predicted labels are higher than the actual labels

## 6. What could be done to improve the model’s accuracy?
     ### Ans. Add more layers and to Train longer: Increase epochs
