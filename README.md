# Partial Residual Networks
This is the implementation of "Enriching Variety of Layer-wise Learning Information by Gradient Combination" using Darknet framwork.

Our [paper](https://github.com/WongKinYiu/PartialResidualNetworks/blob/master/pdf/iccvw-prn.pdf) will be appear in [2019 ICCV Workshop on Low-Power Computer Vision](https://rebootingcomputing.ieee.org/lpirc).

For installing Darknet framework, you can refer to [darknet(pjreddie)](https://github.com/pjreddie/darknet) or [darknet(alexyAB)](https://github.com/AlexeyAB/darknet).

We provide YOLO-v3-tiny-PRN [cfg file](https://github.com/WongKinYiu/PartialResidualNetworks/blob/master/cfg/yolov3-tiny-prn.cfg) and [COCO pre-trained model](https://github.com/WongKinYiu/PartialResidualNetworks/blob/master/model/yolov3-tiny-prn.weights).
You can use provided files to get following results on COCO test-dev set:

| Model | mAP@0.5 | BFLOPs | # Parameter | GPU FPS | CPU FPS |
| :-- | :-: | :-- | :-- | :-- | :-- |
| YOLO-v3-tiny | 33.1 | 5.571 | 8.86M | 300 | 8 |
| YOLO-v3-tiny-PRN | 33.1 | 3.467 | 4.95M | 370 | 13 |

We also provide [cfg file](https://github.com/AlexeyAB/darknet/files/3504727/enet-coco.cfg.txt) and [COCO pre-trained model](https://drive.google.com/open?id=1FlHeQjWEQVJt0ay1PVsiuuMzmtNyv36m) for morden backbone [EfficientNet_b0](https://arxiv.org/abs/1905.11946).
For training this model, you should install [darknet(alexyAB)](https://github.com/AlexeyAB/darknet).

| Model | Size | mAP@0.5 | BFLOPs |
| :-- | :-: | :-: | :-- |
| EfficientNet_b0-PRN | 416x416 | 45.5 | 3.730 |
| EfficientNet_b0-PRN | 320x320 | 41.0 | 2.208 |

# Acknowledgements
[https://github.com/AlexeyAB/darknet](https://github.com/AlexeyAB/darknet)
