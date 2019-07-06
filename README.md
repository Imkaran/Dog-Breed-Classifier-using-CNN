# Dog-Breed-Classifier-using-CNN
This application can classify a dog breed and also tells us whether image contain human or dog or not of them

 Requirements:
1. OpenCV
2. Tensorflow = 1.12
3. Keras (latest version)

Dataset:

Dog Images:https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip

Human Images:https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip

Bottlenect Feature :

Resnet50 : https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogResnet50Data.npz

Vgg16 : https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogVGG16Data.npz

The above alogorithm train on only 100 epochs and gives an test accuracy of around 70-80%.

This algorithm is trained on 133 classess by 
  1. defining own CNN architetcure
  2. using transfer learning
 
