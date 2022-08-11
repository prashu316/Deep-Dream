# Deep-Dream

## Aim
To create a "Deep Dream" version of an image, but what exactly is meant by deep dream? According to google, DeepDream is a computer vision program created by Google engineer Alexander Mordvintsev that uses a convolutional neural network to find and enhance patterns in images via algorithmic pareidolia, thus creating a dream-like appearance reminiscent of a psychedelic experience in the deliberately overprocessed images.

## Methodology
A short note on the working: The significance of this model is that it doesn't update any of the weights when the image is given as input, instead it morphs the image in such a way that the model detects more or less of a feature(eg. edges) in the image therefore resulting in a higher activation for a certain layer as compared to the previous iteration. Note that the model employed is a substantially well trained, pre-trained network and not one made from scratch! 

## Libraries Used
Tensorflow and Keras

## Dataset Details
A single input image. The image is passed into a pretrained Neural Network.

## Output
Base Image:

![base](https://user-images.githubusercontent.com/57295909/183945886-265a924a-270b-499f-8670-1f23647c7919.jpeg)

Output Image:

![sky_dream](https://user-images.githubusercontent.com/57295909/183945983-13fb7c39-5030-42fc-9883-72c38b04efc9.png)
