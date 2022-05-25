# Mix-up--data-augmentation-
there is a technique for data augmentation is called Mix-up , its paper was published in 2018 , the well know technique for data augmentation is cropping flipping , rotation ,scaling , but Mix-up is a different , lets assume we are classifying images of dogs and cats, and we are given a set of images for each of them with labels 1 for dogs and 0 for cats , what we are going to do is mixing up between the two classes images  

its equations are:

newImage = alpha * image1 + (1-alpha) * image2

newLabels = alpha * target1 + (1-alpha) * target2



according to alpha you choose , you determine how the output image looks like and This provides continuous samples of data in between the different classes which expand the distribution of your training data and makes your model more robust 



so why to use MixUp ?

its good at regularizing your models for computer vision tasks and its easy and simple

