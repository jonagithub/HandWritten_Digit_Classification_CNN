# HandWritten_Digit_Classification_CNN

# Handwritten Digit Classification from MNIST Dataset Task 
- Implemented simple ANN with softmax activation function for an output node
- Created different models to analyze the change in accuracy and visualized training and validation loss along with training and validation accuracy of each model
- For instance, model 1 had only input and output layer and got an accuracy of 92.61%  and loss: 2.698%
- In model 2 and 3, after adding one more hidden layer with 100 node with relu as activation function, accuracy came to be 97.46%, 97.560% and loss: 0.908% and 0.8914%, respectively
- In model 4, after adding 3 layers with 128, 64, and 32 nodes between input and output layers, the accuracy came 97.60 and loss was 0.10%   

# Handwritten Digit Classification from MNIST Dataset Task Updated
- Implemented a predictive system to give an own test image on Handwritten Digit Classification task
- In the initial version Handwritten_Digit_Classification.ipynb, I formatted an input image, converting it from RGB to grayscale, resizing it to 28x28 pixels, scaling it to the pixel values and feeding the formatted image as input model to observe the digit prediction 
- In an updated version of Handwritten_Digit_Classification_Updated.ipynb, I further refined the project by creating a dedicated function that processes and predicts images.
- The function takes an input image path and pre-trained model as arguments and is used to make predictions for input_data from the ‘images’ folder in the main directory
- The model used for predictions was trained on the training data, and this updated version allowed for predictions on both the test data and user-given images from the ‘images’ folder
- The training data accuracy came to be 99.46% and testing data accuracy came to be 97.68%       
