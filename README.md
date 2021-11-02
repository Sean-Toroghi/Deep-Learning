<h1> Deep-Learning </h1>

Inspired by [the morning paper](https://blog.acolyer.org/about/) and the [D.L. paper repository]() I find it ver convenient to have a repository of papers at Github.

Table of contents
-----------------

<h3>Computer vision</h3>


<!--ts-->
  * [YOLO](#YOLO)
    * [YOLO.v1](#YOLOv1)
    * [YOLO.v2](#YOLOv2)
    * [YOLO.v3](#YOLOv3)
    * [YOLO.v4](#YOLOv4)
    * [YOLO.v5](#YOLOv5)
<!--te-->

<h3>Sequence modeling</h3>

* [Keras TNC: "An Empirical Evaluation of Generic Convolutional and Recurrent Networks for Sequence Modeling".](#Keras-TNC)


<h2>Computer vision</h2>

YOLO.v1
----

YOLO.v2
-------

-  refined the design and made use of predefined anchor boxes to improve bounding box proposal
- imlementation [link](https://github.com/allanzelener/YAD2K)


YOLO.v3
-------
- further refined the model architecture and training process
- implementation [link](https://github.com/experiencor/keras-yolo3)
- pre-trained weight [link](https://pjreddie.com/media/files/yolov3.weights)
   - based on _DarkNet_ model architecture and loosly VGG-16.
- create the model via [Python script](https://raw.githubusercontent.com/experiencor/keras-yolo3/master/yolo3_one_file_to_detect_them_all.py)
   - make model `make_yolov3_model()`
   - load weights `.load_weights(model)`
   - create block of layers `function _conv_block()`
   - 



YOLO.v4
-------

YOLO.v5
-------
- implementation [link](https://github.com/ultralytics/yolov5)


---

<h2>Sequence modeling</h2>

Keras TNC
-------
"An Empirical Evaluation of Generic Convolutional and Recurrent Networks for Sequence Modeling". 

[Paper link](https://arxiv.org/pdf/1803.01271.pdf)





