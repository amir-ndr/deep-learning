"You Only Look Once" (YOLO) is a popular algorithm because it achieves high accuracy while also being able to run in real-time.
This algorithm "only looks once" at the image in the sense that it requires only one forward propagation pass through the network to make predictions.
After non-max suppression, it then outputs recognized objects together with the bounding boxes.
we used a pre-trained model (a CNN) to encode a 608x608x3 image to 19x19x5x85 tensor image, which 5 inducates the number of anchors and 85 shows our classes and its scores.
at the end using non-max and some threshold we can predict the object in the input image.
