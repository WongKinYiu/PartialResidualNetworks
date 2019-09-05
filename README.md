# Partial Residual Networks
This is the implementation of "Enriching Variety of Layer-wise Learning Information by Gradient Combination" using Darknet framwork.

Our [paper](https://github.com/WongKinYiu/PartialResidualNetworks/blob/master/pdf/iccvw-prn.pdf) will be appear in [2019 ICCV Workshop on Low-Power Computer Vision](https://rebootingcomputing.ieee.org/lpirc).

For installing Darknet framework, you can refer to [darknet(pjreddie)](https://github.com/pjreddie/darknet) or [darknet(AlexeyAB)](https://github.com/AlexeyAB/darknet).

We provide YOLO-v3-tiny-PRN [cfg file](https://github.com/WongKinYiu/PartialResidualNetworks/blob/master/cfg/yolov3-tiny-prn.cfg) and [COCO pre-trained model](https://github.com/WongKinYiu/PartialResidualNetworks/blob/master/model/yolov3-tiny-prn.weights).
You can use provided files to get following results on COCO test-dev set:

| Model | mAP@0.5 | BFLOPs | # Parameter | GPU FPS | CPU FPS |
| :-- | :-: | :-- | :-- | :-- | :-- |
| YOLO-v3-tiny [[1]](https://arxiv.org/abs/1804.02767) | 33.1 | 5.571 | 8.86M | 300 | 8 |
| YOLO-v3-tiny-PRN | 33.1 | 3.467 | 4.95M | 370 | 13 |

We also provide [cfg file](https://github.com/AlexeyAB/darknet/files/3504727/enet-coco.cfg.txt) and [COCO pre-trained model](https://drive.google.com/open?id=1FlHeQjWEQVJt0ay1PVsiuuMzmtNyv36m) for morden backbone [EfficientNet_b0](https://arxiv.org/abs/1905.11946) [[2]](https://arxiv.org/abs/1905.11946).
For training this model, you should install [darknet(AlexeyAB)](https://github.com/AlexeyAB/darknet).

| Model | Size | mAP@0.5 | BFLOPs |
| :-- | :-: | :-: | :-- |
| EfficientNet_b0-PRN | 416x416 | 45.5 | 3.730 |
| EfficientNet_b0-PRN | 320x320 | 41.0 | 2.208 |

Here we provide some experimental results on COCO test-dev set which are not listed in the paper.

| Model | Size | mAP@0.5 | BFLOPs | # Parameter |
| :-- | :-: | :-: | :-- | :-- |
| Pelee [[3]](https://arxiv.org/abs/1804.06882) | 304x304 | 38.3 | 2.58 | 5.98M |
| Pelee-PRN | 320x320 | 40.9 | 2.39 | 3.16M |
| Pelee-YOLOv3 [[1]](https://arxiv.org/abs/1804.02767) | 320x320 | 41.4 | 2.99 | 3.91M |
| Pelee-FPN [[4]](https://arxiv.org/abs/1612.03144) | 320x320 | 41.4 | 2.86 | 3.75M |
| Pelee-PRN-3l | 320x320 | 42.5 | 3.98 | 3.36M |
| mPelee-PRN | 320x320 | 42.7 | 2.82 | 3.81M |

| Model | Size | mAP@0.5 | BFLOPs | # Parameter |
| :-- | :-: | :-: | :-- | :-- |
| Pelee-PRN | 416x416 | 45.0 | 4.04 | 3.16M |
| Pelee-YOLOv3 [[1]](https://arxiv.org/abs/1804.02767) | 416x416 | 45.3 | 5.06 | 3.91M |
| Pelee-FPN [[4]](https://arxiv.org/abs/1612.03144) | 416x416 | 45.7 | 4.84 | 3.75M |
| Pelee-PRN-3l | 416x416 | 46.3 | 5.03 | 3.36M |
| mPelee-PRN | 416x416 | 46.8 | 4.76 | 3.81M |

# Reference
[1] Redmon, J., & Farhadi, A. (2018). Yolov3: An incremental improvement. arXiv preprint arXiv:1804.02767.

[2] Tan, M., & Le, Q. V. (2019). EfficientNet: Rethinking Model Scaling for Convolutional Neural Networks. arXiv preprint arXiv:1905.11946.

[3] Wang, R. J., Li, X., & Ling, C. X. (2018). Pelee: A real-time object detection system on mobile devices. In Advances in Neural Information Processing Systems (pp. 1963-1972).

[4] Lin, T. Y., Dollár, P., Girshick, R., He, K., Hariharan, B., & Belongie, S. (2017). Feature pyramid networks for object detection. In Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (pp. 2117-2125).

# Acknowledgements
[https://github.com/AlexeyAB/darknet](https://github.com/AlexeyAB/darknet)
