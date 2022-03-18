# BAM
Unofficial PyTorch implementation of "BAM (Bottleneck Attention Module)" with training CIFAR-10 

## Introduction
This repository provides the jupyter notebook version of [PyTorch](https://pytorch.org/) implementation of the following paper:
> [Park J, Woo S, Lee J Y, Kweon I S. BAM: Bottleneck Attention Module. 2018. BMVC2018](https://arxiv.org/pdf/1807.06514.pdf)

## Requirments
* [Python 3.6](https://www.continuum.io/downloads)
* [PyTorch 1.7.1](http://pytorch.org/)

## Results
The current results for CIFAR-10 classification is summarized below.

#### CIFAR-10 (Top-1 accuracy (%))
Models         | Training          | Test              |
-------------  | ----------------- | ----------------- |
ResNet50       | 99.83             | 92.55             |
ResNet50-BAM   | 99.84             | 93.99             |

## Reference
* [Official PyTorch code](https://github.com/Jongchan/attention-module)
* [Unofficial PyTorch code](https://github.com/asdf2kr/BAM-CBAM-pytorch)
