# Keras 2 + Python 3.5 with Tensorflow - CNN Example

Tutorial website: https://elitedatascience.com/keras-tutorial-deep-learning-in-python

## Points to note
- I am using Keras 2 + Tensorflow
- In the model building stage, if you follow the tutorial, you will encounter an error that said the shape is incorrect.  According to the author, it is because you are using Tensorflow, not Theano, which means you need extra description on how the data should be handled.
- So you will see `model.add(Convolution2D(32, (3, 3), activation='relu', input_shape=(1,28,28), data_format="channels_first"))`
- Pay attention to the end of `data_format="channels_first"`, this is the magic trick.
- As described in the code, I terminate the training process at the end so you cannot see the training result, it is intented.

Good luck to your deep learning journey
