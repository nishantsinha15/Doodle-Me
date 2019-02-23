# Google-Quick-Draw
Some ML model using the quick draw dataset of google

## Idea 1
A doodle camera. 
Inspired by https://danmacnish.com/2018/07/01/draw-this/. But our model to work with mobile cameras. 

### Important Resources
1. Pretrained weights for object detection - https://ai.googleblog.com/2017/06/supercharge-your-computer-vision-models.html
    Github repo - https://github.com/tensorflow/models/tree/master/research/object_detection
2. The actual github repo https://github.com/danmacnish/cartoonify
3. Demo similar to our work interest(Super awesome) - https://www.kapwing.com/cartoonify 
4. Keras code and models for Object Detection SSD - https://github.com/pierluigiferrari/ssd_keras

## Pipeline (Tentative)
1. Use some pre-trained model for object detection.
2. Align the classes in the Object detection model with those in our Quickdraw datset.
3. Find closest image from the detected class of the quickdraw dataset.
