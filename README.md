# Undergraduate-Research-Project
I created a convolutional neural network that was capable of identifying the tips of concentric tube robots from images.

The images of the CNN are unavailable for distribution at this time, so the code is not functioning or would require you to have your own images.
However it may still be beneficial to you if you're looking to set up a convolutional neural network of your own, as this code is a great resource on 
properly utilizing Pytorch and Tensorboard.

This code uses Pytorch to create a custom dataset, as well as create custom augmentations to apply to this dataset. The code shows the proper format to 
use when accessing data within the dataset, as well as how to make custom compatible augmentations. The code is commented well and can be a great resource
to those just learning convolutional neural networks. 

The code also utilizes Tensorboard to create a graph that continously updates with the loss of the CNN throughout training, validation, and testing. 
Tensorboard is a great as an interactive resource as it allows you to plot multiple loss functions on one graph, as well as save your logs so that it is
easy to pull up again and continue editing. 

I hope you find this code useful in helping to learn convolutional neural networks, before you go to read the code there are a couple of important notes:
- This code was created in Google Colab, due to this there are some additional steps thaat were necessary to run Tensorboard. This may make the code written
incompatible with other IDEs.
- For the convolutional neural network itself, AlexNet was used. I in no way shape or form designed this network, but thought there was no point designing a
custom network for a simple identification task when so many are well established. 
