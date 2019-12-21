# Results of our implementations

| Model | Size | #Param. | FLOPs | AP | AP50 | AP75 |
| :-- | :-: | :-: | :-: | :-: | :-: | :-: |
| Pelee-YOLOv3-tiny [1][2] | 320 | 3.91M | 2.99B | 21.2 | 41.4 | 19.9 |
| Pelee-YOLOv3-tiny [2] | 416 | 3.91M | 5.06B | 23.6 | 45.3 | 22.5 |
| Pelee-FPN [3] | 320 | 3.75M | 2.86B | 21.3 | 41.4 | 20.0 |
| Pelee-FPN [3] | 416 | 3.75M | 4.84B | 23.9 | 45.7 | 22.7 |
| Pelee-PRN [4] | 320 | 3.16M | 2.39B | 20.9 | 40.9 | 19.4 |
| Pelee-PRN [4] | 416 | 3.16M | 4.04B | 23.3 | 45.0 | 22.0 |
| Pelee-PRN-3l [4] | 320 | 3.36M | 3.98B | 21.2 | 42.5 | 19.8 |
| Pelee-PRN-3l [4] | 416 | 3.36M | 5.03B | 24.1 | 46.3 | 22.9 |
| Pelee-PAN [5] | 320 | - | 2.95B | 21.4 | 41.6 | 20.2 |
| Pelee-PAN [5] | 416 | - | 4.99B | 24.1 | 45.9 | 23.2 |
| Pelee-PAN2 [5] | 320 | - | 2.56B | 21.4 | 41.6 | 20.2 |
| Pelee-PAN2 [5] | 416 | - | 4.33B | 23.6 | 45.4 | 22.5 |
| Pelee2-PRN (private) | 320 | 3.81M | 2.82B | 22.2 | 42.7 | 21.0 |
| Pelee2-PRN (private) | 416 | 3.81M | 4.76B | 24.8 | 46.8 | 24.0 |
| Pelee2-PRN-GIoU (private) [6] | 320 | 3.81M | 2.82B | 24.4 | 41.6 | 25.3 |
| Pelee2-PRN-GIoU (private) [6] | 416 | 3.81M | 4.76B | 26.8 | 45.3 | 28.1 |
| Pelee2-PRN-GIoU-Scale (private) | 416 | 3.81M | 4.76B | 26.9 | 45.5 | 28.0 |
| Pelee2-SPP-PRN (private) [7] | 320 | - | 2.88B | 22.1 | 42.6 | 20.8 |
| Pelee2-SPP-PRN (private) [7] | 416 | - | 4.86B | 24.7 | 47.1 | 23.6 |
| Pelee2-SPP-PRN-GIoU-Scale (private) | o320 | - | 2.88B | 24.9 | 43.6 | 25.6 |
| Pelee2-SPP-PRN-GIoU-Scale (private) | 416 | - | 4.86B | 27.3 | 46.4 | 28.5 |
| Pelee2-PRN-GIoU-Mixup (private) [8] | 320 | 3.81M | 2.82B | 22.4 | 39.2 | 22.9 |
| Pelee2-PRN-GIoU-Mixup (private) [8] | 416 | 3.81M | 4.76B | 24.3 | 42.1 | 24.9 |
| SparsePelee-PRN [9] | 320 | - | 2.16B | 20.3 | 40.0 | 18.7 |
| SparsePelee-PRN [9] | 416 | - | 3.65B | 22.7 | 44.1 | 21.3 |
| PartialPelee-PRN (private) | 320 | - | 2.17B | 20.5 | 40.2 | 19.1 |
| PartialPelee-PRN (private) | 416 | - | 3.67B | 22.7 | 44.0 | 21.4 |
| PartialXPelee-PRN (private) | 416 | - | 4.17B | 25.2 | 47.2 | 24.6 |
| Pelee2-TridentNet (private) [10] | 320 | - | 3.63B | 22.6 | 42.7 | 21.6 |
| Pelee2-TridentNet (private) [10] | 416 | - | 6.14B | 25.5 | 47.0 | 25.2 |
| Pelee2-CEM (private) [11] | 320 | - | 2.85B | 21.4 | 41.2 | 20.2 |
| Pelee2-CEM (private) [11] | 416 | - | 4.81B | 23.7 | 45.2 | 22.8 |
| Pelee2-CEM-SAM (private) [11] | 320 | - | 2.90B | 21.5 | 42.0 | 20.3 |
| Pelee2-CEM-SAM (private) [11] | 416 | - | 4.90B | 24.2 | 46.1 | 23.3 |
| Pelee2-CEM-SAM-One (private) [11] | 416 | - | 4.95B | 25.5 | 48.0 | 24.2 |
| Pelee2-DC-SPP (private) [12] | 320 | - | 2.81B | 20.0 | 38.8 | 18.9 |
| Pelee2-DC-SPP (private) [12] | 416 | - | 4.75B | 23.2 | 43.7 | 22.4 |
| Pelee-ReCORE (private) | 320 | - | 2.86B | 21.6 | 42.6 | 19.7 |
| Pelee-ReCORE (private) | 416 | - | 4.82B | 23.9 | 46.0 | 22.5 |
| Pelee-ReCORE-BiF (private) | 320 | - | 3.15B | 24.3 | 45.8 | 23.6 |
| Pelee-ReCORE-BiF (private) | 416 | - | 5.32B | 26.7 | 49.5 | 26.3 |
| Pelee-ReCORE-BiF-Scale (private) | 416 | - | 5.32B | 26.7 | 49.6 | 26.4 |
| Pelee-ReCORE-BiF-GIoU (private) | 416 | - | 5.32B | 26.8 | 45.7 | 27.7 |
| Pelee-ReCORE-BiF-GIoU-Scale (private) | 416 | - | 5.32B | 27.4 | 46.6 | 28.5 |
| Pelee-ReBiF (private) | 416 | - | 6.63B | 26.6 | 48.8 | 26.4 |
| Pelee-ReBiF-Scale (private) | 416 | - | 6.63B | 26.9 | 49.1 | 26.5 |
| Pelee-ReBiF-GIoU (private) | 416 | - | 6.63B | 26.9 | 45.4 | 28.0 |
| Pelee-ReBiF-GIoU-Scale (private) | 416 | - | 6.63B | 27.5 | 46.2 | 28.6 |

[1] Wang, R. J., Li, X., & Ling, C. X. (2018). Pelee: A real-time object detection system on mobile devices. In Advances in Neural Information Processing Systems (pp. 1963-1972).

[2] Redmon, J., & Farhadi, A. (2018). Yolov3: An incremental improvement. arXiv preprint arXiv:1804.02767.

[3] Lin, T. Y., Dollár, P., Girshick, R., He, K., Hariharan, B., & Belongie, S. (2017). Feature pyramid networks for object detection. In Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (pp. 2117-2125).

[4] Wang, C. Y., Mark Liao, H. Y., Chen, P. Y., & Hsieh, J. W. (2019). Enriching Variety of Layer-wise Learning Information by Gradient Combination. In Proceedings of the IEEE International Conference on Computer Vision Workshops (pp. 0-0).

[5] Liu, S., Qi, L., Qin, H., Shi, J., & Jia, J. (2018). Path aggregation network for instance segmentation. In Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (pp. 8759-8768).

[6] Rezatofighi, H., Tsoi, N., Gwak, J., Sadeghian, A., Reid, I., & Savarese, S. (2019). Generalized Intersection over Union: A Metric and A Loss for Bounding Box Regression. In Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition.

[7] He, K., Zhang, X., Ren, S., & Sun, J. (2015). Spatial pyramid pooling in deep convolutional networks for visual recognition. IEEE transactions on pattern analysis and machine intelligence, 37(9), 1904-1916.

[8] Zhang, Z., He, T., Zhang, H., Zhang, Z., Xie, J., & Li, M. (2019). Bag of Freebies for Training Object Detection Neural Networks. arXiv preprint arXiv:1902.04103.

[9] Zhu, L., Deng, R., Maire, M., Deng, Z., Mori, G., & Tan, P. (2019). Sparsely Aggregated Convolutional Networks. In Proceedings of the European Conference on Computer Vision.

[10] Li, Y., Chen, Y., Wang, N., & Zhang, Z. (2019). Scale-Aware Trident Networks for Object Detection. arXiv preprint arXiv:1901.01892.

[11] Qin, Z., Li, Z., Zhang, Z., Bao, Y., Yu, G., Peng, Y., & Sun, J. (2019). ThunderNet: Towards Real-time Generic Object Detection. arXiv preprint arXiv:1903.11752.

[12] Huang, Z., & Wang, J. (2019). DC-SPP-YOLO: Dense Connection and Spatial Pyramid Pooling Based YOLO for Object Detection. arXiv preprint arXiv:1903.08589.
