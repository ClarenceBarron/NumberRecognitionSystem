# NumberRecognitionSystem
Project for CPE 4903 that is supposed to recognize handwritten numbers through a CNN model using the Keras library.


In order to use this system you need the following:
- Raspberry Pi 4
- Camera
- Paper with Hand Written numbers (preferably in Sharpie)

When turning on, the model is already pre-trained regarding testing. (I will upload the test code here as well so you can test this on your own machine). When ran, the code will first train the CNN (Convolutional Neural Network) model using the data given to us by the keras cloud using the MNIST data. Once learning, all you have to do is insert a photo with in the image, so we can predict the model.

The model will run through the data and learn. Upon prediction, we will classify that model using some NumPy functions. Afterward, we will get a class. That class will give us the number and the confidence level. The confidence level will show how accurate the model was in predicting the given number.
