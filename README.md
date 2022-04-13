# classification-of-blinding-retinal-diseases-resnet
In this project, I compare three neural networks for classifying three different retinal diseases. 
The data consists of more than 32 thousand optical coherence tomography (OCT) images of the retina separated equally in four classes across train/val/test datasets.
Two of of the neural networks consist of a combination of resnet layers and convolutional layers. 
The third network is a plain convolutional network. I use Global Average Pooling(GAP) and no fully connected (FC) layers in all of the models.
The best training loss that I achieved is 9.88% on the shallower architecture with residual blocks. 
I had a problem with overfitting during the whole process. Tuning was focused on adjusting the learning rate.
