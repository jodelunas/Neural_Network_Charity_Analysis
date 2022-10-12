# Neural_Network_Charity_Analysis

## Analysis Overview
The purpose of this project is to use deep-learning neural networks with the TensorFlow platform in Python, to analyze and classify the success of charitable donations.
I used the following methods for the analysis:

  * preprocessing the data for the neural network model,
  * compile, train and evaluate the model,
  * optimize the model.

## Results

### Data Preprocessing
 * The columns EIN and NAME are identification information and have been removed from the input data.
 * The column IS_SUCCESSFUL contains binary data refering to weither or not the charity donation was used effectively.    This variable is then considered as the target for our deep learning neural network.
 * The following columns APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT,      SPECIAL_CONSIDERATIONS, ASK_AMT are the features for our model.
* Encoding of the categorical variables, spliting into training and testing datasets and standardization have been  applied to the features.

### Compiling, Training, and Evaluating the Model
 * This deep-learning neural network model is made of two hidden layers with 80 and 30 neurons respectively. The output layer is made of a unique neuron as it is a binary classification.
I used the activation function ReLU for the hidden layers. Sigmoid is used on the output layer.
For the compilation, the optimizer is adam and the loss function is binary_crossentropy.
 * The model accuracy is under 75%. This is not a satisfying performance to help predict the outcome of the charity donations.
 * To increase the performance of the model, I increased the number of neurons on one of the hidden layers, then I used a model with three hidden layers. I also tried a different activation function (tanh), but none of these steps helped improve the model's performance.

### Summary

Everything I tried for the deep-learning neural network module did not produce an acceptable outcome. I could increase or decrease the number of epochs used. I could also use more hidden layers. It might mean I need to try something other than deep-learning. I could use a supervised machine learning model, such as the Random Forest Classifier, to combine a multitude of decision trees to generate a classified output and evaluate its performance against the deep learning model.
