# Awesome-GANs with Tensorflow [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)[![Build Status](https://travis-ci.org/dwyl/esta.svg?branch=master)](https://travis-ci.org/)
Tensorflow implementation of GANs(Generative Adversarial Networks)

## Test Environments
* OS : Windows 10 Edu x86-64 / Linux Ubuntu 16.04 x86-64
* CPU : i7-7700K, GPU : GTX 1060 6GB
* Tensorflow 1.4.0 with CUDA 8.0 + cuDNN 7.0
* Python 3.5+

## Prerequisites
* python 3.5+
* tensorflow 1.4.0
* scipy
* pillow
* h5py
* pickle
* glob, tqdm
* sklearn
* Internet :)

## Usage
    (before running train.py, make sure run after downloading dataset & changing dataset directory in train.py)
    just download it and run train.py
    $ python3 xxx_train.py

## DataSets
Now supporting(?) DataSets are... (code is in /datasets.py)
* MNIST 
* CiFar-10
* CiFar-100
* Celeb-A
* pix2pix shoes
* pix2pix bags
* ImageNet
* (more DataSets will be added soon!)

## Repo Tree
```
│
├── gan_img (generated images)
│   ├── train_xxx.png
│   └── train_xxx.png
├── model (model)
│   ├── checkpoint
│   ├── ...
│   └── xxx.ckpt
├── gan_model.py (gan model)
├── gan_train.py (gan trainer)
├── dataset.py   (DataSet loader)
├── gan_tb.png   (Tensor-Board result)
└── readme.md    (results & explains)
```

## Papers & Codes

*Name* | *Summary* | *Paper* | *Code*
:---: | :---: | :---: | :---:
**ACGAN**        | *Auxiliary Classifier Generative Adversarial Networks* | [[arXiv]](https://arxiv.org/abs/1610.09585) | [[code]](https://github.com/kozistr/Awesome-GANs/blob/master/ACGAN)
**AdaGAN**       | *Boosting Generative Models* | [[arXiv]](https://arxiv.org/abs/1701.02386) |
**BEGAN**        | *Boundary Equilibrium Generative Adversarial Networks* | [[arXiv]](https://arxiv.org/abs/1703.10717) | [[code]](https://github.com/kozistr/Awesome-GANs/blob/master/BEGAN)
**BGAN**         | *Boundary-Seeking Generative Adversarial Networks* | [[arXiv]](https://arxiv.org/abs/1702.08431) | [[code]](https://github.com/kozistr/Awesome-GANs/blob/master/BGAN)
**CGAN**         | *Conditional Generative Adversarial Networks* | [[arXiv]](https://arxiv.org/abs/1411.1784) | [[code]](https://github.com/kozistr/Awesome-GANs/blob/master/CGAN)
**CoGAN**        | *Coupled Generative Adversarial Networks* | [[arXiv]](https://arxiv.org/abs/1606.07536) |
**CycleGAN**     | *Unpaired img2img translation using Cycle-consistent Adversarial Networks* | [[arXiv]](https://arxiv.org/pdf/1703.10593.pdf) |
**DCGAN**        | *Deep Convolutional Generative Adversarial Networks* | [[arXiv]](https://arxiv.org/abs/1511.06434) | [[code]](https://github.com/kozistr/Awesome-GANs/blob/master/DCGAN)
**DiscoGAN**     | *Discover Cross-Domain Generative Adversarial Networks* | [[arXiv]](https://arxiv.org/abs/1703.05192) | 
**EBGAN**        | *Energy-based Generative Adversarial Networks* | [[arXiv]](https://arxiv.org/abs/1609.03126) | [[code]](https://github.com/kozistr/Awesome-GANs/blob/master/EBGAN)
**f-GAN**        | *Training Generative Neural Samplers using Variational Divergence Minimization* | [[arXiv]](https://arxiv.org/abs/1606.00709) |
**GAN**          | *Generative Adversarial Networks* | [[arXiv]](https://arxiv.org/abs/1406.2661) | [[code]](https://github.com/kozistr/Awesome-GANs/blob/master/GAN)
**Softmax GAN**  | *Generative Adversarial Networks with Softmax* | [[arXiv]](https://arxiv.org/pdf/1704.06191.pdf) | [[code]](https://github.com/kozistr/Awesome-GANs/blob/master/GAN)
**3D GAN**       | *3D Generative Adversarial Networks* | [[MIT]](http://3dgan.csail.mit.edu/) |
**GAP**          | *Generative Adversarial Parallelization* | [[arXiv]](https://arxiv.org/abs/1612.04021) |
**GEGAN**        | *Generalization and Equilibrium in Generative Adversarial Networks* | [[arXiv]](https://arxiv.org/abs/1703.00573) |
**InfoGAN**      | *Interpretable Representation Learning by Information Maximizing Generative Adversarial Networks* | [[arXiv]](https://arxiv.org/abs/1606.03657) | [[code]](https://github.com/kozistr/Awesome-GANs/blob/master/InfoGAN)
**LAPGAN**       | *Laplacian Pyramid Generative Adversarial Networks* | [[arXiv]](https://arxiv.org/abs/1506.05751) | [[code]](https://github.com/kozistr/Awesome-GANs/blob/master/LAPGAN)
**LSGAN**        | *Loss-Sensitive Generative Adversarial Networks* | [[arXiv]](https://arxiv.org/abs/1701.06264) | [[code]](https://github.com/kozistr/Awesome-GANs/blob/master/LSGAN)
**MAGAN**        | *Margin Adaptation for Generative Adversarial Networks* | [[arXiv]](https://arxiv.org/abs/1704.03817) | [[code]](https://github.com/kozistr/Awesome-GANs/blob/master/MAGAN)
**MRGAN**        | *Mode Regularized Generative Adversarial Networks* | [[arXiv]](https://arxiv.org/abs/1612.02136) |
**SalGAN**       | *Visual Saliency Prediction Generative Adversarial Networks* | [[arXiv]](https://arxiv.org/abs/1701.01081) |
**SeqGAN**       | *Sequence Generative Adversarial Networks with Policy Gradient* | [[arXiv]](https://arxiv.org/abs/1609.05473) |
**SGAN**         | *Stacked Generative Adversarial Networks* | [[arXiv]](https://arxiv.org/abs/1612.04357) | [[code]](https://github.com/kozistr/Awesome-GANs/blob/master/SGAN)
**SGAN++**       | *Realistic Image Synthesis with Stacked Generative Adversarial Networks* | [[arXiv]](https://arxiv.org/pdf/1710.10916.pdf) | 
**SRGAN**        | *Photo-Realistic Single Image Super-Resolution Using a Generative Adversarial Network* | [[arXiv]](https://arxiv.org/pdf/1609.04802.pdf) | [[code]](https://github.com/kozistr/Awesome-GANs/blob/master/SRGAN)
**StarGAN**      | *Unified Generative Adversarial Networks for Multi-Domain Image-to-Image Translation* | [[arXiv]](https://arxiv.org/abs/1711.09020) | 
**WGAN**         | *Wasserstein Generative Adversarial Networks* | [[arXiv]](https://arxiv.org/abs/1701.07875) | [[code]](https://github.com/kozistr/Awesome-GANs/blob/master/WGAN)
**ImprovedWGAN** | *Improved Training of Wasserstein Generative Adversarial Networks* | [[arXiv]](https://arxiv.org/abs/1704.00028) | [[code]](https://github.com/kozistr/Awesome-GANs/blob/master/WGAN)

## Author
HyeongChan Kim / ([@kozistr](https://kozistr.github.io), [@zer0day](http://zer0day.tistory.com))
