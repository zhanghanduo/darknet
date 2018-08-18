![Darknet Logo](http://pjreddie.com/media/files/darknet-black-small.png)

# 1-Channel YOLOV3 #

### Introduction

Darknet is an open source neural network framework written in C and CUDA. It is fast, easy to install, and supports CPU and GPU computation.

This is a **forked** version to implement object detection using YOLO version 3 to adapt to gray-scale images.

For basic information see the [Darknet project website](http://pjreddie.com/darknet).


### Roadmap

- [x] Read images (either 3-channel or 1-channel)
- [x] Convert 3-channel pre-trained weights into 1-channel
- [x] Convert 3-channel network structure into 1-channel
- [x] Validate the correctness
- [ ] Validate the improvement

**Note:** if error `Out of memory` occurs then in `.cfg`-file you should increase `subdivisions=16`, 32 or 64: [link](https://github.com/AlexeyAB/darknet/blob/0039fd26786ab5f71d5af725fc18b3f521e7acfd/cfg/yolov3.cfg#L4)