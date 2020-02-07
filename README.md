# Accelerometer Movement Prediction using Multitask Learning 

- The input of here is time series of three axes of an accelerometer
- The output is one of the 21 classes of accelerometer movement 

## Multitask Learning 

Multitask learning is the concept of using deep learning based model, and training it to perform more than one tasks. like using the same training data to perform multiple tasks like humans do all the time. 
The tasks have been divided into <b>Main Task </b> and <b>Auxiliary Task</b>
It has been observed that the performance of the model in executing the main task improves because of the auxiliary task, as the model is able to get more knowledge from the data. 

## The Case 

Here we are creating new losses for our model to predict. These will be our auxiliary tasks with the main tasks remaining as Classification of movements 

## Dependencies 
1. numpy 
2. pandas 
3. sklearn 
4. Keras 
5. Tensorflow 2.0


link to the [dataset](https://archive.ics.uci.edu/ml/datasets/Dataset+for+ADL+Recognition+with+Wrist-worn+Accelerometer)


