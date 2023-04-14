# ICP-10
Recording Link: https://drive.google.com/file/d/1t5hG4upfzOAvGe1duLDVCYrZuW5_3zeT/view?usp=share_link

Use case: Sentiment Analysis on the Twitter data set:
To perform sentiment analysis on the Twitter dataset using an LSTM model, I have followed these steps:
Preprocess the data: Clean the text, tokenize it, and encode it in a format suitable for use with an LSTM model.
Split the data into training and validation sets.
Build the LSTM model
Train the model: Use the training data to fit the model to the data, adjusting the model's weights to minimize the loss function.
Predict on new data: Load the saved model and use it to make predictions on new text data, such as the example provided in the prompt. Load the Twitter dataset and preprocess it.
Define the architecture of an LSTM model.
Use GridSearchCV to search over a range of hyperparameters for the LSTM model, such as the number of LSTM layers, the number of units in each layer, and the learning rate.
Train the LSTM model using the best hyperparameters found by GridSearchCV.
Evaluate the performance of the trained model on a validation set.
Save the trained model to disk.
Use the saved model to predict on new text data, such as the example provided in the prompt.
