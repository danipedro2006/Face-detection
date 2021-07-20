# Java Face Detection
> Image recognition, focusing on face detection.

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Status](#status)
* [Contact](#contact)

## General info
This app is about the fundamental concept of image recognition, focusing on face detection. This
topic is getting very hot nowadays because these learning algorithms can be used in several fields from
software engineering to crime investigation.

Face detection applications use algorithms and ML to find human faces within larger images, which often incorporate other non-face objects such as landscapes, buildings and other human body parts like feet or hands. Face detection algorithms typically start by searching for human eyes -- one of the easiest features to detect. The algorithm might then attempt to detect eyebrows, the mouth, nose, nostrils and the iris. Once the algorithm concludes that it has found a facial region, it applies additional tests to confirm that it has, in fact, detected a face.

The Viola-Jones framework is based on training a model to understand what is and is not a face. Once trained, the model extracts specific features, which are then stored in a file so that features from new images can be compared with the previously stored features at various stages. If the image under study passes through each stage of the feature comparison, then a face has been detected and operations can proceed.

Although the Viola-Jones framework is still popular for recognizing faces in real-time applications, it has limitations. For example, the framework might not work if a face is covered with a mask or scarf, or if a face is not properly oriented, then the algorithm might not be able to find it. To help eliminate the drawbacks of the Viola-Jones framework and improve face detection, other algorithms -- such as region-based convolutional neural network (R-CNN) and Single Shot Detector (SSD) -- have been developed to help improve processes.

Find more on this topic from my [article on pubhtml5.com](https://online.pubhtml5.com/knij/zeuj/#p=3) digital platform 

## Screenshots
[Click-me!](https://github.com/danipedro2006/Face-detection/blob/master/Screen-Recording-_12-6-2019-12-29-41-PM_.gif)

## Technologies
* Basic Java - version 1.8
* Java GUI programming
* OpenCV library
* Viola-Jones algorithms
* Haar-features

## Status
Project is completed and no longer maintained.

## Contact
Created by @Danisoft Arad 2020(https://danipedro2006.github.io/) - feel free to contact me!