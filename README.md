# Handwritten Digit Classification
A model which can identify the handwritten digits by classifying them 

## Dataset Used:-
MNIST dataset(Modified National Institute of Standards and Technology)

The MNIST database contains 60,000 training images, 10,000 testing images

## Process
1) Preprocessing(Reshaping and Normalizing the Images) :-
   Reshaping the array to 4-dims so that it can work with the KerasAPI(greyscale image ), Need to normalize our data as it is always required in neural      network models, by dividing the RGB codes to 255
   
2) Building the Convolutional Neural Network
   Layers:- a)Flatten b)Dense 3)Output 4)Softmax 
   
3) Compiling and training the model
   Compiling the model takes three parameters: Optimizer(Adam), Loss and Metrics
   
4) Evaluating the Model

## Result of the final model
  Loss: 0.0789 - Accuracy: 0.9744
