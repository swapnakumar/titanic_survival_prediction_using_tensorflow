# Titanic Survival Prediction using Tensorflow
In this code, I want you to show how you can use the **Tensorflow** to train **Titanic Dataset**, a model that can give the prediction of surviving passengers.

# Titanic Dataset
In 1912, the ship RMS Titanic struck an iceberg on its maiden voyage and sank, resulting in the deaths of most of its passengers and crew. In this project, we will explore that what features best predict whether someone survived or did not survive.

The titanic data is divided into two parts:
1. Training data(train.csv)
2. Testing data(test.csv)

The training data should be used to build our model and testing data should be used to check how well our model performs on unseen data.

# Problem:
Predict the survival of passengers in Titanic.

# Prerequisites
1. Tensorflow
2. Numpy
3. Pandas
4. Sklearn
5. Matplotlib

# Description
TensorFlow’s API (tf.contrib.learn) is used to configure, train, and evaluate the models. In this, we’ll use tf.contrib.learn to construct a neural network classifier and train it on the **Titanic dataset** to predict the survival of passengers in Titanic.

In this firstly we'll load the Titanic data to Tensorflow, using the pandas **pd.read_csv** method, In this 50% of the dataset is divided into training data and 50% into testing data.

Next, we'll built a neural network classifier using the tf.contrib.learn

tf.contrib.learn offers the variety of predifined models, called Estimator which can be used for training and evaluating the model.

Now then after configuring our model, now we'll fit the model.

In the end, the model thus predict the survival of the passengers in Titanic
