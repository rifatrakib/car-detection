# More on Machine Learning & Deep Learning

Find more of my deep learning models on the following links:

- [Emoji Generator](https://github.com/Rakib1508/emojify)
- [Face Recognition](https://github.com/Rakib1508/face-recognition)
- [Machine Translation](https://github.com/Rakib1508/machine-translation)
- [Neural Style Transfer](https://github.com/Rakib1508/neural-style-transfer)
- [Trigger Word Detection](https://github.com/Rakib1508/trigger-word-detection)
- [Word Vector Representation](https://github.com/Rakib1508/word-vector-representation)

More ML/DL models in the following links:

- [Fundamental Machine Learning Models](https://github.com/Rakib1508/ml-projects)
- [Simple Deep Learning models](https://github.com/Rakib1508/dl-projects)
- [Machine Learning with MatLab](https://github.com/Rakib1508/Machine-Learning)

# Car Detection

A simple autonomous driving implementation using python and jupyter notebook. In this notebook, you will learn about object detection using the very powerful YOLO model. Many of the ideas in this notebook are described in the two YOLO papers:

[Redmon et al., 2016](https://arxiv.org/abs/1506.02640) and [Redmon and Farhadi, 2016](https://arxiv.org/abs/1612.08242).

## Important

Please download the dataset from the following link, and put it in the `model_data` folder.
[Download Dataset](https://www.amazon.com/clouddrive/share/BXZyHxor8eS2MH0XdcrsHXStPaL56lQGIjlEYlIp4GC)

#### This project deals with:

- Use object detection on a car detection dataset using YOLO algorithm.
- Deal with bounding boxes.
- YOLO is a state-of-the-art object detection model that is fast and accurate.
- It runs an input image through a CNN which outputs a 19x19x5x85 dimensional volume.
- The encoding can be seen as a grid where each of the 19x19 cells contains information about 5 boxes.
- You filter through all the boxes using non-max suppression. Specifically:
  - Score thresholding on the probability of detecting a class to keep only accurate (high probability) boxes
  - Intersection over Union (IoU) thresholding to eliminate overlapping boxes.
- Because training a YOLO model from randomly initialized weights is non-trivial and requires a large dataset as well as lot of computation, we used previously trained model parameters in this notebook.

#### References:

The ideas presented in this notebook came primarily from the two YOLO papers. The implementation here also took significant inspiration and used many components from Allan Zelener's GitHub repository. The pre-trained weights used in this exercise came from the official YOLO website.

- Joseph Redmon, Santosh Divvala, Ross Girshick, Ali Farhadi - [You Only Look Once: Unified, Real-Time Object Detection](https://arxiv.org/abs/1506.02640) (2015)
- Joseph Redmon, Ali Farhadi - [YOLO9000: Better, Faster, Stronger](https://arxiv.org/abs/1612.08242) (2016)
- Allan Zelener - [YAD2K: Yet Another Darknet 2 Keras](https://github.com/allanzelener/YAD2K)
- The official YOLO website [https://pjreddie.com/darknet/yolo/](https://pjreddie.com/darknet/yolo/)

The Drive.ai Sample Dataset (provided by drive.ai) is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/). We are grateful to Brody Huval, Chih Hu and Rahul Patel for providing this data.
