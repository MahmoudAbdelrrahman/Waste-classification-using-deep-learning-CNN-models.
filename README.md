# Waste-classification-using-deep-learning-CNN-models.

In this study, it is aimed to develop a deep learning application which detects types of garbage to provide recyclability with vision system. 
Training and testing will be performed with image data consisting of several classes based on the number of types we are classifying to.

1-DenseNet121
DenseNet is one of the new discoveries in neural networks for visual 
object recognition. DenseNet is quite like ResNet with some 
fundamental differences. ResNet uses an additive 
method that merges the previous layer (identity) with the future layer, 
whereas DenseNet concatenates the output of the previous layer with the 
future layer.
DenseNet was developed specifically to improve the declined accuracy 
caused by the vanishing gradient in high-level neural networks. In 
simpler terms, due to the longer path between the input layer and the 
output layer, the information vanishes before reaching its destination.

2-ResNet50v2 Model Architecture:
The core difference between DenseNet121 and this model 
that ResNet uses an additive method that merges the 
previous layer (identity) with the future layer, whereas 
DenseNet concatenates the output of the previous layer 
with the future layer as mentioned before.

References:
1- https://www.sciencedirect.com/science/article/pii/S2352914820302537
2- https://keras.io/api/applications/resnet/
3- https://www.tensorflow.org/api_docs/python/tf/keras/applications/resnet50/ResNet50
4- https://keras.io/api/applications/densenet/
5- https://www.pluralsight.com/guides/introduction-to-densenet-with-tensorflow
6- https://towardsdatascience.com/creating-densenet-121-with-tensorflow-edbc08a956d8
7- https://towardsdatascience.com/understanding-and-coding-a-resnet-in-keras-446d7ff84d33
