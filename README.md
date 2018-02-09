# ImageClassificationSummary
A summary for state-of-the-art image-classifying methods on CIFAR-10, CIFAR-100 and ImageNet-1K


## CIFAR

| Method                | Depth | Params | CIFAR-10 | CIFAR-100 |
|-----------------------|:-----:|:------:|:--------:|:---------:|
| Deeply Supervised Net [1] | -     | -      | 7.97%    | 34.57%    |
| Highway Network [2]       | -     | -      | 7.72%    | 32.39%    |
| FractalNet           [3]  | 21    | 38.6M  | 5.22%    | 23.30%    |
| FractalNet (Dropout) [3]  | 21    | 38.6M  | 4.60%    | 23.73%    |
| ResNet-110  [4]           | 110   | 1.7M   | 6.43%    | -         |
| ResNet-1202 [4]           | 1202  | 19.4M  | 7.93%    | -         |
| preact-ResNet-164   [5]   | 164   | 1.7M   | 5.46%    | 24.33%    |
| preact-ResNet-1001  [5]   | 1001  | 10.7M  | 4.92%    | 22.71%    |
| WRN-28-10           [6]   | 28    | 36.5M  | 4.00%    | 19.25%    |
| WRN-28-10 (dropout) [6]   | 28    | 36.5M  | 3.89%    | 18.85%    |
| AttentionNet-92  [7]      | 92    | 1.9M   | 4.99%    | 21.71%    |
| AttentionNet-236 [7]      | 236   | 5.1M   | 4.14%    | 21.16%    |
| AttentionNet-452 [7]      | 452   | 8.6M   | 3.90%    | 20.45%    |
| ResNeXt-29, 8×64d  [8]    | 29    | 34.4M  | 3.65%    | 17.77%    |
| ResNeXt-29, 16×64d [8]    | 29    | 68.1M  | 3.58%    | 17.31%    |
| DenseNet-BC (k = 12) [9]  | 100   | 0.8M   | 4.51%    | 22.27%    |
| DenseNet-BC (k = 24) [9]  | 250   | 15.3M  | 3.62%    | 17.60%    |
| DenseNet-BC (k = 40) [9]  | 190   | 25.6M  | 3.46%    | 17.18%    |

## Reference

[1] Lee, Chen-Yu, Saining Xie, Patrick Gallagher, Zhengyou Zhang, and Zhuowen Tu. "Deeply-supervised nets." In Artificial Intelligence and Statistics, pp. 562-570. 2015.

[2] Srivastava, Rupesh Kumar, Klaus Greff, and Jürgen Schmidhuber. "Highway networks." arXiv preprint arXiv:1505.00387 (2015).

[3] Larsson, Gustav, Michael Maire, and Gregory Shakhnarovich. "Fractalnet: Ultra-deep neural networks without residuals." arXiv preprint arXiv:1605.07648 (2016).

[4] He, Kaiming, Xiangyu Zhang, Shaoqing Ren, and Jian Sun. "Deep residual learning for image recognition." In Proceedings of the IEEE conference on computer vision and pattern recognition, pp. 770-778. 2016.

[5] He, Kaiming, Xiangyu Zhang, Shaoqing Ren, and Jian Sun. "Identity mappings in deep residual networks." In European Conference on Computer Vision, pp. 630-645. Springer, Cham, 2016.

[6] Zagoruyko, Sergey, and Nikos Komodakis. "Wide residual networks." arXiv preprint arXiv:1605.07146 (2016).

[7] Wang, Fei, Mengqing Jiang, Chen Qian, Shuo Yang, Cheng Li, Honggang Zhang, Xiaogang Wang, and Xiaoou Tang. "Residual attention network for image classification." arXiv preprint arXiv:1704.06904 (2017).

[8] Xie, Saining, Ross Girshick, Piotr Dollár, Zhuowen Tu, and Kaiming He. "Aggregated residual transformations for deep neural networks." In Computer Vision and Pattern Recognition (CVPR), 2017 IEEE Conference on, pp. 5987-5995. IEEE, 2017.

[9] Huang, Gao, Zhuang Liu, Kilian Q. Weinberger, and Laurens van der Maaten. "Densely connected convolutional networks." In Computer Vision and Pattern Recognition (CVPR), 2017 IEEE Conference on, 2017.
