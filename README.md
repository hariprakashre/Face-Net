# Face-Net
As a part of the project i have done the following:
>DEEP LEARNING COURSES ON COURSERA

>Read RESNET, INCEPTIONNET, MOBILENETv2 papers to understand how CNN's work

>Read FACENET, DEEPFACE papers to understand how face learning algorithms work

The coursera courses for learning about Deep learning works using neural networks and use of cnns for facial recognition and how it becomes complex on going deeper into the networks from edge detection to complex figures

Read Resnet to understand how adding residual to next layer helps the cnns to get better accuracy and faster optimisation without much increase in computation and no increase in weights required to be trained

Read Inception net to see how using many convulations on the layer help extract many features at the same time making the accuracy higher and better with a managable increase in computation

Read Mobilenet to see how the computation can be reduced so much such that even mobilephones can do these computation at a faster rate with a small sacrifice of accuracy

Read Deepface to see how the triangulation and making the image into a 3d projection and using siamese networks help recognize people better

Read Facenet to see how triplet loss of selecting 2 images of a specific person and one of some one looking same but not the same person and use them to find weights using cnns such that only the correct person can be recognised

Implemented harr.py on LFW(Labeled Faces in the wild) dataset to crop the images using opencv so that only faces are present in the images without other things being disturbing the weights to be learnt

Implemented Facenet paper using Tensorflow library and added layers in the model using the weights pretrained on imagenet, 2 models of resnet and Xception present in the application of keras and with additional layers trained the data using triplet loss and plotted the cost vs number of iterations to see how the weights got better to decrease the cost 
