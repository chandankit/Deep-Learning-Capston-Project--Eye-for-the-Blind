# Deep-Learning-Capston-Project--Eye-for-the-Blind
## Objective: 
(Blind people can understand any image with the help of speech) The idea is to build a product that can explain the features of a product contents of an image in the form of speech. This model is a use case for blind people and can help them understand any image with the help of speech.
This problem statement is an application of both deep learning and natural language processing. The features of an image will be extracted by the CNN-based encoder, and this will be decoded by an RNN model.

## Data size:
consists of a sentence-based image description having a list of 8,000 images that are each paired with five different captions, which provide clear descriptions of the salient entities and events of the image.

## The project pipeline can be briefly summarised in the following four steps:

Data understanding: Here, you need to load the data and understand the representation.
Data preprocessing: In this step, you will process both images and captions in the desired format.
Train/Test split: Combine both images and captions to create the train and test data sets.
Model building: This is the stage where you will create your image captioning model by building the Encoder, Attention and Decoder model
Model evaluation: Evaluate the models using greedy search and the BLEU score.
