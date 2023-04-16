# Death Age Prediction
Repository for Death Clock, Hackathon event in GDSC WOW

This model uses Tensorflow Framework to predict death age of a person. It is trained based on the [Mortality Dataset](https://www.kaggle.com/datasets/rajanand/mortality).

## Working
I recognised this as a time-series forecast type of problem so based on that I chose the type of loss function used in the model. 

A sequential model was made using the Tensorflow Framework.

Overall Mean Squared Error of 14.6203 and loss of 12.0086 was obtained using Mean Absolute Error as Loss Function and making three layers using Sigmoid, Relu and Swish Activation Functions.
