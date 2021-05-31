# Eye-For-Blind

## Problem statement: 

To create a deep learning model that can explain the content of an image in the form of speech through caption generation with the attention mechanism on the Flickr8K data set 

This type of model is a use case for blind people so that they can understand any image with the help of speech. The caption generated through a CNN-RNN model will be converted to speech using a text-to-speech library. 

This problem statement is an application of both deep learning and natural language processing. The features of an image will be extracted by the CNN-based encoder, and this will be decoded by an RNN model.

The project is an extended application of Show, Attend and Tell: Neural Image Caption Generation with Visual Attention.paper.https://arxiv.org/abs/1502.03044

The data set is taken from the Kaggle website and consists of a sentence-based image description having a list of 8,000 images that are each paired with five different captions, which provide clear descriptions of the salient entities and events of the image. https://www.kaggle.com/adityajn105/flickr8k
