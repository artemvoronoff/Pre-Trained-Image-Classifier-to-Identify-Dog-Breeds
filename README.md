# Pre-Trained-Image-Classifier-to-Identify-Dog-Breeds
This project will use to create image classifier to identify dog breeds.

# Important Notes:
The image classification aplication will be using a deep learning model called "convolutional neural network (CNN)". CNN's are traditionally powerhouses in detecting features
in images like colors, textures and edges--which inherently helps in identifying objects in images. We will be incorporation a dataset of 1.2 million images from [ImageNet](https://image-net.org/index.php).

In this project we will be utilizing AlexNet, VGG and Resnet (as our CNNs). They are located in the ```classifier.py``` file.

### Additional Information:
The more images of two similar looking dog breeds that the algorithm has "learned" from, the more likely the algorithm will be able to distringuish between those two breeds. We have found the following breeds to look very similiar: *Great Pyrenees, Kuvasz, German Shepherd, Malinois, Beagle, and Walker Hound* 


## Main Objectives
1.) Identifying which pet images are of dogs and which pet images aren't of dogs.
2.) Classifying the breeds of dogs, for the images that are of dogs.

For objective 1, notice that both ```VGG``` and ```AlexNet``` correctly identify images of "dogs" and "not-a-dog" 100% of the time.
For objective 2, ```VGG``` provides the best solution because it classifies the correct breed of dog over 90% of the time.
