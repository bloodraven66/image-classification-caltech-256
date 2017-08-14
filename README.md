# Image Classification Experiments on Caltech-256 dataset
## 

| model | accuracy, % | top 5 accuracy, %| number of parameters |
| --- | --- | --- | --- | 
| DenseNet-121    | 85 | 96 | 7,216,256 |
| DenseNet-121 with trained ternary quantization | 71 | 89 | ~7M 2-bit |
| DenseNet-201    | 87 | 97 | 18,584,704 |
| ResNet-18 | 81 | 94 | 11,307,840 |
| ResNet-18 with stochastic depth | 65 | 85 | 11,307,840 |
| SqueezeNet v1.1 | 66 | 85 | 853824 | 
| SqueezeNet v1.1 with entropy regularization | 66 | 86 | 853824 |
| Delegating classifiers | 77 | 93 | - |

## Trained ternary quantization

## Stochastic depth

## Entropy regularization

## Delegating classifiers

## Notes
* Cyclical Cosine Annealing

## Requirements
* Python 3.5
* pytorch 0.2
* torchvision, Pillow
* numpy, pandas, sklearn, matplotlib, tqdm

## References
[1] [Regularizing Neural Networks by Penalizing Confident Output Distributions](https://arxiv.org/abs/1701.06548)

[2] [Trained Ternary Quantization](https://arxiv.org/abs/1612.01064)

[3] [Deep Networks with Stochastic Depth](https://arxiv.org/abs/1603.09382)
