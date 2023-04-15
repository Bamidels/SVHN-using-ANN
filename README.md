# SVHN-using-ANN
Summary:
The project is about developing an Artificial Neural Network (ANN) model to recognize the house numbers in the Street View House Numbers (SVHN) dataset. The dataset consists of 60,000 images of digits and their corresponding labels. The aim is to build an accurate classification model that can correctly identify the digits in the images.

Dependencies:

Google Colab
Pandas
Numpy
Matplotlib
Seaborn
Scikit-learn
Tensorflow
h5py
Project Workflow:

Load the SVHN dataset using h5py and split it into training and testing sets.
Visualize the first 10 images and their corresponding labels from the training dataset.
Prepare the data by reshaping and normalizing the input data and one-hot encoding the target variable.
Build and compile an ANN model with two different architectures.
Fit the models on the training dataset and validate them on the validation dataset.
Evaluate the performance of the models using the classification report and confusion matrix on the test dataset.
Provide final observations on the results obtained.
Results/Outputs:
The outputs of the project include:

Visualizations of the first 10 images and their labels from the training dataset.
The summary of the model architecture for both models.
Plots of the accuracy and loss of both models during training.
The classification report and confusion matrix of the predictions made on the test dataset.
Final observations on the performance of the models.
References:

SVHN Dataset: http://ufldl.stanford.edu/housenumbers/
TensorFlow Documentation: https://www.tensorflow.org/api_docs
Scikit-Learn Documentation: https://scikit-learn.org/stable/documentation.html
