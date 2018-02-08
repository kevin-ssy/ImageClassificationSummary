# ImageClassificationSummary
A summary for state-of-the-art image-classifying methods on CIFAR-10, CIFAR-100 and ImageNet-1K


## CIFAR

| Method                | Depth | Params | CIFAR-10 | CIFAR-100 |
|-----------------------|:-----:|:------:|:--------:|:---------:|
| Deeply Supervised Net | -     | -      | 7.97%    | 34.57%    |
| Highway Network       | -     | -      | 7.72%    | 32.39%    |
| FractalNet            | 21    | 38.6M  | 5.22%    | 23.30%    |
| FractalNet (Dropout)  | 21    | 38.6M  | 4.60%    | 23.73%    |
| ResNet-110            | 110   | 1.7M   | 6.43%    | -         |
| ResNet-1202           | 1202  | 19.4M  | 7.93%    | -         |
| preact-ResNet-164     | 164   | 1.7M   | 5.46%    | 24.33%    |
| preact-ResNet-1001    | 1001  | 10.7M  | 4.92%    | 22.71%    |
| WRN-28-10             | 28    | 36.5M  | 4.00%    | 19.25%    |
| WRN-28-10 (dropout)   | 28    | 36.5M  | 3.89%    | 18.85%    |
| AttentionNet          | 92    | 1.9M   | 4.99%    | 21.71%    |
| AttentionNet-236      | 236   | 5.1M   | 4.14%    | 21.16%    |
| Attention-452         | 452   | 8.6M   | 3.90%    | 20.45%    |
| ResNeXt-29, 8×64d     | 29    | 34.4M  | 3.65%    | 17.77%    |
| ResNeXt-29, 16×64d    | 29    | 68.1M  | 3.58%    | 17.31%    |
| DenseNet-BC (k = 12)  | 100   | 0.8M   | 4.51%    | 22.27%    |
| DenseNet-BC (k = 24)  | 250   | 15.3M  | 3.62%    | 17.60%    |
| DenseNet-BC (k = 40)  | 190   | 25.6M  | 3.46%    | 17.18%    |
