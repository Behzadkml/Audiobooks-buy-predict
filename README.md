# Audiobooks buy predict
#Data Loading and Preprocessing:

Load the raw CSV data.
Split the data into inputs and targets.
Balance the dataset by ensuring the number of examples for each class is equal.
Scale the input features.
Shuffle the dataset.
Split the data into training, validation, and test sets.
Save the preprocessed datasets to disk.
Model Definition:

Define a simple neural network model using TensorFlow/Keras with two hidden layers and an output layer.
Compile the model with the Adam optimizer, sparse categorical cross-entropy loss, and accuracy as a metric.
Model Training:

Train the model using the training data.
Validate the model on the validation data after each epoch.
 
