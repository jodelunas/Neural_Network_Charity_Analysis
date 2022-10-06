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
